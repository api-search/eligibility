---
api_specs:
- filename: xeneta-air-api-openapi.yml
  format: yaml
  label: Xeneta Air API
  slug: xeneta-air-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xeneta/openapi/xeneta-air-api-openapi.yml
- filename: xeneta-ocean-api-openapi.yml
  format: yaml
  label: Xeneta Ocean API
  slug: xeneta-ocean-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xeneta/openapi/xeneta-ocean-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the legal entity stated on the Order Form (the “Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Large shippers excluded from API information
    text: make the Information available to anyone who ships 2,500 TEUs (ocean freight) or 1,500 tonnes (air freight) per year or more.
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
name: Xeneta
provenance_date: '2026-11-10'
provider_name: Xeneta
provider_slug: xeneta
slug: xeneta-eligibility
source_date: '2026-11-10'
source_filename: xeneta-eligibility.yml
source_heading: Eligibility
source_page: https://www.xeneta.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xeneta\naid: xeneta\nurl: https://www.xeneta.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the legal entity stated on the Order Form (the “Customer”)\nrestricted_uses:\n- summary: Large shippers excluded from API information\n  text: make the Information available to anyone who ships 2,500 TEUs (ocean freight) or 1,500 tonnes (air freight)\n    per year or more.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xeneta/eligibility/xeneta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Xeneta's own page on 2026-11-10.
synthetic: false
tags:
- Freight
- Shipping
- Logistics
- Ocean Freight
- Air Freight
- Benchmarking
- Market Data
- Supply Chain
- Rates
- Emissions
---
