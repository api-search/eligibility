---
api_specs:
- filename: tado-openapi-generated.yml
  format: yaml
  label: tado API
  slug: tado-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tado/openapi/_ae-authored/tado-openapi-generated.yml
- filename: tado-me-api-openapi.yml
  format: yaml
  label: tado Me API
  slug: tado-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tado/openapi/tado-me-api-openapi.yml
- filename: tado-oauth2-api-openapi.yml
  format: yaml
  label: tado Oauth2 API
  slug: tado-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tado/openapi/tado-oauth2-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Deliveries shall only take place to delivery addresses in countries listed on https://support.tado.com/articles/4345196 .
  entity_types:
  - text: these are deemed to be natural persons placing orders that cannot be attributed to commercial, independent or freelance activity.
    type: individual
  - text: '"businesses" are natural or legal persons or partnerships with legal personality pursuing commercial, independent or freelance activities.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Household quantities only
    text: We sell our products exclusively in customary household quantities.
  - summary: Energy Savings Promise limited to private use
    text: The “Energy Savings Promise” applies exclusively to consumers ordering in standard quantities for private household use.
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
name: tado
provenance_date: '2026-11-10'
provider_name: tado
provider_slug: tado
slug: tado-eligibility
source_date: '2026-11-10'
source_filename: tado-eligibility.yml
source_heading: Eligibility
source_page: https://www.tado.com/en/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tado\naid: tado\nurl: https://www.tado.com/en/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Deliveries shall only take place to delivery addresses in countries listed on https://support.tado.com/articles/4345196\n    .\nentity_types:\n- type: individual\n  text: these are deemed to be natural persons placing orders that cannot be attributed to commercial, independent\n    or freelance activity.\n- type: business\n  text: '\"businesses\" are natural or legal persons or partnerships with legal personality pursuing commercial, independent\n    or freelance\
  \ activities.'\nrestricted_uses:\n- summary: Household quantities only\n  text: We sell our products exclusively in customary household quantities.\n- summary: Energy Savings Promise limited to private use\n  text: The “Energy Savings Promise” applies exclusively to consumers ordering in standard quantities for private\n    household use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tado/eligibility/tado-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from tado's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Smart Home
- Heating
- EnergySaving
- IoT
---
