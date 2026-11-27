---
api_specs:
- filename: flexa-assets-api-openapi.yml
  format: yaml
  label: Flexa Assets API
  slug: flexa-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexa/openapi/flexa-assets-api-openapi.yml
- filename: flexa-commerce-intents-api-openapi.yml
  format: yaml
  label: Flexa Commerce Intents API
  slug: flexa-commerce-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexa/openapi/flexa-commerce-intents-api-openapi.yml
- filename: flexa-events-api-openapi.yml
  format: yaml
  label: Flexa Events API
  slug: flexa-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexa/openapi/flexa-events-api-openapi.yml
- filename: flexa-refunds-api-openapi.yml
  format: yaml
  label: Flexa Refunds API
  slug: flexa-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexa/openapi/flexa-refunds-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled or operated from within the United States. Flexa makes no representation that the Services ... is appropriate or available for use outside the United States
  entity_types:
  - text: You must be 13 years of age or older to register for an account and make use of the Services.
    type: individual
  minimum_age:
    text: You must be 13 years of age or older to register for an account and make use of the Services.
    value: '13'
  restricted_uses:
  - summary: Illegal use
    text: you agree that you will not use the Services if such use is prohibited or otherwise violates the laws of the country, state, province, territory, or other jurisdiction in which you reside
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You authorize us, directly or through third parties, to make any inquiries we consider necessary to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flexa
provenance_date: '2026-11-09'
provider_name: Flexa
provider_slug: flexa
slug: flexa-eligibility
source_date: '2026-11-09'
source_filename: flexa-eligibility.yml
source_heading: Eligibility
source_page: https://flexa.co/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flexa\naid: flexa\nurl: https://flexa.co/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled or operated from within the United States. Flexa makes no representation that\n    the Services ... is appropriate or available for use outside the United States\nentity_types:\n- type: individual\n  text: You must be 13 years of age or older to register for an account and make use of the Services.\nrestricted_uses:\n- summary: Illegal use\n  text: you agree that you will not use the Services if such use is prohibited or otherwise violates the laws of\n\
  \    the country, state, province, territory, or other jurisdiction in which you reside\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You authorize us, directly or through third parties, to make any inquiries we consider necessary to verify\n    your identity.\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older to register for an account and make use of the Services.\n"
source_yaml_url: https://artifacts.apis.io/flexa/eligibility/flexa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Flexa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Digital Currency
- Fintech
- Blockchain
- Merchant Payments
- Web3
---
