---
api_specs:
- filename: blackbird-app-api-openapi.yml
  format: yaml
  label: Blackbird App API
  slug: blackbird-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-app-api-openapi.yml
- filename: blackbird-challenges-api-openapi.yml
  format: yaml
  label: Blackbird Challenges API
  slug: blackbird-challenges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-challenges-api-openapi.yml
- filename: blackbird-check-ins-api-openapi.yml
  format: yaml
  label: Blackbird Check-ins API
  slug: blackbird-check-ins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-check-ins-api-openapi.yml
- filename: blackbird-locations-api-openapi.yml
  format: yaml
  label: Blackbird Locations API
  slug: blackbird-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-locations-api-openapi.yml
- filename: blackbird-memberships-api-openapi.yml
  format: yaml
  label: Blackbird Memberships API
  slug: blackbird-memberships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-memberships-api-openapi.yml
- filename: blackbird-payments-api-openapi.yml
  format: yaml
  label: Blackbird Payments API
  slug: blackbird-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-payments-api-openapi.yml
- filename: blackbird-restaurants-api-openapi.yml
  format: yaml
  label: Blackbird Restaurants API
  slug: blackbird-restaurants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-restaurants-api-openapi.yml
- filename: blackbird-rewards-api-openapi.yml
  format: yaml
  label: Blackbird Rewards API
  slug: blackbird-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-rewards-api-openapi.yml
- filename: blackbird-specials-api-openapi.yml
  format: yaml
  label: Blackbird Specials API
  slug: blackbird-specials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-specials-api-openapi.yml
- filename: blackbird-users-api-openapi.yml
  format: yaml
  label: Blackbird Users API
  slug: blackbird-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blackbird/openapi/blackbird-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Offerings are provided for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: The Offerings are intended only for users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Non-personal or commercial use needs consent
    text: Any other use of the Offerings requires the prior written consent of Company.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blackbird
provenance_date: '2026-11-09'
provider_name: Blackbird
provider_slug: blackbird
slug: blackbird-eligibility
source_date: '2026-11-09'
source_filename: blackbird-eligibility.yml
source_heading: Eligibility
source_page: https://www.blackbird.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blackbird\naid: blackbird\nurl: https://www.blackbird.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Offerings are provided for your personal and non-commercial use.\nrestricted_uses:\n- summary: Non-personal or commercial use needs consent\n  text: Any other use of the Offerings requires the prior written consent of Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Offerings are intended only for users who are eighteen\
  \ (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/blackbird/eligibility/blackbird-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Blackbird's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- Loyalty
- Payments
- Dining
- Membership
- Cryptocurrency
- Blockchain
- Web3
---
