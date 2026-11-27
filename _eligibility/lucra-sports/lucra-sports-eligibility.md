---
api_specs:
- filename: lucra-sports-health-api-openapi.yml
  format: yaml
  label: Lucra Sports Health API
  slug: lucra-sports-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-health-api-openapi.yml
- filename: lucra-sports-locations-api-openapi.yml
  format: yaml
  label: Lucra Sports Locations API
  slug: lucra-sports-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-locations-api-openapi.yml
- filename: lucra-sports-recreational-games-api-openapi.yml
  format: yaml
  label: Lucra Sports Recreational Games API
  slug: lucra-sports-recreational-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-recreational-games-api-openapi.yml
- filename: lucra-sports-states-api-openapi.yml
  format: yaml
  label: Lucra Sports States API
  slug: lucra-sports-states-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-states-api-openapi.yml
- filename: lucra-sports-tenanttaggroups-api-openapi.yml
  format: yaml
  label: Lucra Sports Tenant Tag Groups API
  slug: lucra-sports-tenanttaggroups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-tenanttaggroups-api-openapi.yml
- filename: lucra-sports-tournaments-api-openapi.yml
  format: yaml
  label: Lucra Sports Tournaments API
  slug: lucra-sports-tournaments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-tournaments-api-openapi.yml
- filename: lucra-sports-tournaments-legacy-api-openapi.yml
  format: yaml
  label: Lucra Sports Tournaments (Legacy) API
  slug: lucra-sports-tournaments-legacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-tournaments-legacy-api-openapi.yml
- filename: lucra-sports-user-score-api-openapi.yml
  format: yaml
  label: Lucra Sports User Score API
  slug: lucra-sports-user-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-user-score-api-openapi.yml
- filename: lucra-sports-webhooks-api-openapi.yml
  format: yaml
  label: Lucra Sports Webhooks API
  slug: lucra-sports-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucra-sports/openapi/lucra-sports-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Persons physically located in any of the fifty (50) states or Washington DC, excluding Arkansas, Connecticut, Delaware, Louisiana, Montana, Nevada, Pennsylvania, and South Dakota, are eligible to open an account and participate in Cash Buy In Contests
  entity_types:
  - text: You participate in the Games strictly in Your personal capacity for recreational and entertainment purposes only
    type: individual
  minimum_age:
    text: You must be at least thirteen (13) years of age (or the minimum legal age in Your jurisdiction, if higher) to access and participate in free-to-play Games, and at least eighteen (18) years of age
    value: '13'
  restricted_uses:
  - summary: Pre-release or confidential information
    text: You are prohibited from playing a Game or entering a Contest on the Platform if You have access or have had access to any pre-release, confidential information
  - summary: Restricted states
    text: Persons physically present in any state not listed as eligible for a particular Contest type in Sections 3.5.1 through 3.5.4 above may not
  - summary: Bots and fraud
    text: You will not be involved in any fraudulent or other unlawful activity in relation to Your participation in any of the Games
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we, or a third party acting on our behalf, are entitled to conduct any verification checks (including but not limited to age and identity verifications and credit background checks)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lucra Sports
provenance_date: '2026-11-09'
provider_name: Lucra Sports
provider_slug: lucra-sports
slug: lucra-sports-eligibility
source_date: '2026-11-09'
source_filename: lucra-sports-eligibility.yml
source_heading: Eligibility
source_page: https://www.playlucra.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lucra Sports\naid: lucra-sports\nurl: https://www.playlucra.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Persons physically located in any of the fifty (50) states or Washington DC, excluding Arkansas, Connecticut,\n    Delaware, Louisiana, Montana, Nevada, Pennsylvania, and South Dakota, are eligible to open an account and participate\n    in Cash Buy In Contests\nentity_types:\n- type: individual\n  text: You participate in the Games strictly in Your personal capacity for recreational and entertainment purposes\n    only\nrestricted_uses:\n\
  - summary: Pre-release or confidential information\n  text: You are prohibited from playing a Game or entering a Contest on the Platform if You have access or have\n    had access to any pre-release, confidential information\n- summary: Restricted states\n  text: Persons physically present in any state not listed as eligible for a particular Contest type in Sections\n    3.5.1 through 3.5.4 above may not\n- summary: Bots and fraud\n  text: You will not be involved in any fraudulent or other unlawful activity in relation to Your participation\n    in any of the Games\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we, or a third party acting on our behalf, are entitled to conduct any verification checks (including but\n    not limited to age and identity verifications and credit background checks)\nminimum_age:\n  value: '13'\n  text: You must be at least thirteen (13) years of age (or the minimum legal age in Your jurisdiction, if higher)\n    to access and\
  \ participate in free-to-play Games, and at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/lucra-sports/eligibility/lucra-sports-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Lucra Sports's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Sports
- Gamification
- Loyalty
- Tournaments
- Contests
- Payments
- Wagering
- Embedded Finance
- SDK
- Webhook
- Compliance
---
