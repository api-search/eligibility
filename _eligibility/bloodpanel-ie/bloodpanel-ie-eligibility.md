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
  - summary: Not for emergency care
    text: Do not use it to seek emergency help or delay getting medical care.
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
name: BloodPanel
provenance_date: '2026-11-09'
provider_name: BloodPanel
provider_slug: bloodpanel-ie
slug: bloodpanel-ie-eligibility
source_date: '2026-11-09'
source_filename: bloodpanel-ie-eligibility.yml
source_heading: Eligibility
source_page: https://bloodpanel.ie/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BloodPanel\naid: bloodpanel-ie\nurl: https://bloodpanel.ie/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for emergency care\n  text: Do not use it to seek emergency help or delay getting medical care.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bloodpanel-ie/eligibility/bloodpanel-ie-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BloodPanel's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Ireland
- Digital Health
- BloodTests
- Artificial Intelligence
---
