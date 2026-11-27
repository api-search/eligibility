---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THESE GENERAL TERMS AND CONDITIONS REPRESENT THE ENTIRE AGREEMENT BETWEEN YOU (“BUYER”) AND COLORCHIP LTD. (“SELLER”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Applications where failure may cause significant injury
    text: No warranty is made with respect to products used in devices intended for use in applications where failure to perform when properly used can reasonably be expected to result in significant injury
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: No order shall bind Seller until accepted by an authorized person in writing.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ColorChip
provenance_date: '2026-11-09'
provider_name: ColorChip
provider_slug: colorchip
slug: colorchip-eligibility
source_date: '2026-11-09'
source_filename: colorchip-eligibility.yml
source_heading: Eligibility
source_page: https://www.color-chip.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ColorChip\naid: colorchip\nurl: https://www.color-chip.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THESE GENERAL TERMS AND CONDITIONS REPRESENT THE ENTIRE AGREEMENT BETWEEN YOU (“BUYER”) AND COLORCHIP LTD.\n    (“SELLER”)\nrestricted_uses:\n- summary: Applications where failure may cause significant injury\n  text: No warranty is made with respect to products used in devices intended for use in applications where failure\n    to perform when properly used can reasonably be expected to result in significant\
  \ injury\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: No order shall bind Seller until accepted by an authorized person in writing.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/colorchip/eligibility/colorchip-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ColorChip's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Optical
- Data Center
- Networking
- Hardware
---
