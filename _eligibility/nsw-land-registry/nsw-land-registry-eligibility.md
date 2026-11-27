---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The terms and conditions apply to all customers (government, professional and private) seeking to lodge Documents in person
    type: government
  minimum_age:
    text: null
    value: null
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
name: NSW Land Registry Services
provenance_date: '2026-11-10'
provider_name: NSW Land Registry Services
provider_slug: nsw-land-registry
slug: nsw-land-registry-eligibility
source_date: '2026-11-10'
source_filename: nsw-land-registry-eligibility.yml
source_heading: Eligibility
source_page: https://nswlrs.com.au/about-us/policies/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NSW Land Registry Services\naid: nsw-land-registry\nurl: https://nswlrs.com.au/about-us/policies/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: The terms and conditions apply to all customers (government, professional and private) seeking to lodge\n    Documents in person\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nsw-land-registry/eligibility/nsw-land-registry-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from NSW Land Registry Services's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Australia
- Land Registry
- Title
- Conveyancing
- Property Records
- Torrens Title
- eConveyancing
- Government
- Geospatial
- PropTech
---
