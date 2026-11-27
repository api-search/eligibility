---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Offer valid in the United States only, does not apply to existing Outgo customers.
  minimum_age:
    text: you are not of legal age to form a binding contract with Outgo
    value: null
  restricted_uses:
  - summary: Commercial use only
    text: Carrier shall only use the Services for commercial, business purposes and shall not use the Services for personal, family or household purposes
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
name: Outgo
provenance_date: '2026-11-10'
provider_name: Outgo
provider_slug: outgo
slug: outgo-eligibility
source_date: '2026-11-10'
source_filename: outgo-eligibility.yml
source_heading: Eligibility
source_page: https://outgo.dat.com/legal/tpb-platform-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outgo\naid: outgo\nurl: https://outgo.dat.com/legal/tpb-platform-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Offer valid in the United States only, does not apply to existing Outgo customers.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use only\n  text: Carrier shall only use the Services for commercial, business purposes and shall not use the Services for\n    personal, family or household purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form\
  \ a binding contract with Outgo\n"
source_yaml_url: https://artifacts.apis.io/outgo/eligibility/outgo-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Outgo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Freight
- Factoring
- Fintech
- Payments
- Logistics
---
