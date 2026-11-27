---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Commercial use by real estate or lending professionals is limited to providing information to consumers via the Services or taking actions on behalf of a client
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lending decisions
    text: lending professionals in lending institutions are prohibited from using the information provided by NAWY through the Services in making any loan-related decisions.
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
name: Nawy
provenance_date: '2026-11-10'
provider_name: Nawy
provider_slug: nawy
slug: nawy-eligibility
source_date: '2026-11-10'
source_filename: nawy-eligibility.yml
source_heading: Eligibility
source_page: https://www.nawy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nawy\naid: nawy\nurl: https://www.nawy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Commercial use by real estate or lending professionals is limited to providing information to consumers\n    via the Services or taking actions on behalf of a client\nrestricted_uses:\n- summary: Lending decisions\n  text: lending professionals in lending institutions are prohibited from using the information provided by NAWY\n    through the Services in making any loan-related decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nawy/eligibility/nawy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Nawy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Real Estate
- PropTech
- Egypt
- Property
- Mortgage
---
