---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Services only for own use
    text: Further, the Services are offered only for your use, and not for the use or benefit of any third party.
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
name: KitchenMate
provenance_date: '2026-11-09'
provider_name: KitchenMate
provider_slug: kitchenmate
slug: kitchenmate-eligibility
source_date: '2026-11-09'
source_filename: kitchenmate-eligibility.yml
source_heading: Eligibility
source_page: https://www.kitchenmate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KitchenMate\naid: kitchenmate\nurl: https://www.kitchenmate.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Services only for own use\n  text: Further, the Services are offered only for your use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/kitchenmate/eligibility/kitchenmate-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from KitchenMate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food and Beverage
- Autonomous Retail
- Vending
- Smart Devices
- IoT
- Workplace Services
- Hardware
---
