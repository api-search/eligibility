---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 13 years of age or older and reside in the United States or any of its territories to use the Services.
  minimum_age:
    text: You must be 13 years of age or older and reside in the United States or any of its territories to use the Services.
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: We hereby permit you to use the Services for your personal non-commercial use only
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
name: UPSIDE Foods
provenance_date: '2026-11-10'
provider_name: UPSIDE Foods
provider_slug: upside-foods
slug: upside-foods-eligibility
source_date: '2026-11-10'
source_filename: upside-foods-eligibility.yml
source_heading: Eligibility
source_page: https://upsidefoods.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UPSIDE Foods\naid: upside-foods\nurl: https://upsidefoods.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 13 years of age or older and reside in the United States or any of its territories to use the\n    Services.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: We hereby permit you to use the Services for your personal non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older and\
  \ reside in the United States or any of its territories to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/upside-foods/eligibility/upside-foods-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from UPSIDE Foods's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Food
- Cultivated Meat
- Alternative Protein
- Biotechnology
- Food Service
---
