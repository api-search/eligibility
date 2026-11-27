---
api_specs:
- filename: playable-campaigns-api-openapi.yml
  format: yaml
  label: Playable Campaigns API
  slug: playable-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/playable/openapi/playable-campaigns-api-openapi.yml
- filename: playable-media-api-openapi.yml
  format: yaml
  label: Playable Media API
  slug: playable-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/playable/openapi/playable-media-api-openapi.yml
- filename: playable-user-api-openapi.yml
  format: yaml
  label: Playable User API
  slug: playable-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/playable/openapi/playable-user-api-openapi.yml
- filename: playable-oauth-api-openapi.yml
  format: yaml
  label: Playable OAUTH API
  slug: playable-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/playable/openapi/playable-oauth-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Participant monetary contributions prohibited
    text: The Customer is prohibited from using the Platform in a manner that requires or solicits participants to make a monetary stake, wager, or any other form of financial contribution as a condition of participation in any campaign.
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
name: Playable
provenance_date: '2026-11-10'
provider_name: Playable
provider_slug: playable
slug: playable-eligibility
source_date: '2026-11-10'
source_filename: playable-eligibility.yml
source_heading: Eligibility
source_page: https://playable.com/terms-and-conditions-v2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Playable\naid: playable\nurl: https://playable.com/terms-and-conditions-v2/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Participant monetary contributions prohibited\n  text: The Customer is prohibited from using the Platform in a manner that requires or solicits participants to\n    make a monetary stake, wager, or any other form of financial contribution as a condition of participation in\n    any campaign.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/playable/eligibility/playable-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Playable's own page on 2026-11-10.
synthetic: false
tags:
- Company
- marketing-gamification
- interactive-marketing
- Campaign Management
- Zero-Party Data
- Lead Generation
- Loyalty
- MarTech
- Webhook
- OAuth
- Authentication
---
