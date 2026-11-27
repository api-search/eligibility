---
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
    text: (e) use or allow the transmission, transfer, export, re-export or other transfer of any product, technology or information it obtains or learns pursuant to this Agreement (or any direct product thereof) in violation of any export control or other laws and regulations of the United States or any other relevant jurisdiction
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
name: SmartKargo
provenance_date: '2026-11-10'
provider_name: SmartKargo
provider_slug: smartkargo
slug: smartkargo-eligibility
source_date: '2026-11-10'
source_filename: smartkargo-eligibility.yml
source_heading: Eligibility
source_page: https://www.smartkargo.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmartKargo\naid: smartkargo\nurl: https://www.smartkargo.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: (e) use or allow the transmission, transfer, export, re-export or other transfer of any product, technology\n    or information it obtains or learns pursuant to this Agreement (or any direct product thereof) in violation\n    of any export control or other laws and regulations of the United States or any other relevant jurisdiction\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smartkargo/eligibility/smartkargo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from SmartKargo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Air Cargo
- E-Commerce
- Software-as-a-Service
---
