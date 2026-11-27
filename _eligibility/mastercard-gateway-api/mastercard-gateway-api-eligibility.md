---
api_specs:
- filename: mastercard-gateway-api-merchant-api-openapi.yml
  format: yaml
  label: Mastercard Gateway API Merchant API
  slug: mastercard-gateway-api-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mastercard-gateway-api/openapi/mastercard-gateway-api-merchant-api-openapi.yml
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
  - summary: Export control compliance
    text: You agree to abide by these laws and regulations as applicable and will not transfer, directly or indirectly, by electronic transmission or otherwise, any content or software from this Site to or from any countries or foreign nations in violation of such laws or regulations.
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
name: Mastercard Gateway API
provenance_date: '2026-11-10'
provider_name: Mastercard Gateway API
provider_slug: mastercard-gateway-api
slug: mastercard-gateway-api-eligibility
source_date: '2026-11-10'
source_filename: mastercard-gateway-api-eligibility.yml
source_heading: Eligibility
source_page: https://developer.mastercard.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mastercard Gateway API\naid: mastercard-gateway-api\nurl: https://developer.mastercard.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: You agree to abide by these laws and regulations as applicable and will not transfer, directly or indirectly,\n    by electronic transmission or otherwise, any content or software from this Site to or from any countries or\n    foreign nations in violation of such laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mastercard-gateway-api/eligibility/mastercard-gateway-api-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Mastercard Gateway API's own page on 2026-11-10.
synthetic: false
tags:
- Credit Cards
- Gateways
- Payment Processing
- Payments
---
