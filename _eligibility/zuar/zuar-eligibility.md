---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least thirteen years old.
    value: '13'
  restricted_uses:
  - summary: Illegal or harmful content
    text: You may not submit content to the forum that is illegal, offensive, or otherwise harmful to others.
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
name: Zuar
provenance_date: '2026-11-10'
provider_name: Zuar
provider_slug: zuar
slug: zuar-eligibility
source_date: '2026-11-10'
source_filename: zuar-eligibility.yml
source_heading: Eligibility
source_page: https://community.zuar.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zuar\naid: zuar\nurl: https://community.zuar.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: You may not submit content to the forum that is illegal, offensive, or otherwise harmful to others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least thirteen years old.\n"
source_yaml_url: https://artifacts.apis.io/zuar/eligibility/zuar-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Zuar's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Analytics
- ETL
- Business Intelligence
- Integration
- Company
---
