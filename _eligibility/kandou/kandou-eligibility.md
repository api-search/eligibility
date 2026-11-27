---
claim_count: 2
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
  - summary: US export and sanctions compliance
    text: you will not — directly or indirectly — sell, export, reexport, transfer, divert, or otherwise dispose of any products, software, or technology
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once we have received your completed Account Registration Form and verified the accuracy of its contents, we will establish your Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kandou
provenance_date: '2026-11-09'
provider_name: Kandou
provider_slug: kandou
slug: kandou-eligibility
source_date: '2026-11-09'
source_filename: kandou-eligibility.yml
source_heading: Eligibility
source_page: https://www.kandou.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kandou\naid: kandou\nurl: https://www.kandou.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: US export and sanctions compliance\n  text: you will not — directly or indirectly — sell, export, reexport, transfer, divert, or otherwise dispose of\n    any products, software, or technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once we have received your completed Account Registration Form and verified the accuracy of its contents,\n    we will establish your Account\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kandou/eligibility/kandou-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Kandou's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Semiconductors
- Hardware
- Chiplets
- Interconnect
- SerDes
- AI Infrastructure
- Deep Tech
---
