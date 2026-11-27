---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Create an account or post any content if you are not over 13 years of age
    value: '13'
  restricted_uses:
  - summary: Multiple trial accounts
    text: Creating multiple accounts or organizations to obtain additional Trials is strictly prohibited.
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
name: Finicom
provenance_date: '2026-11-09'
provider_name: Finicom
provider_slug: finicom
slug: finicom-eligibility
source_date: '2026-11-09'
source_filename: finicom-eligibility.yml
source_heading: Eligibility
source_page: https://finicom.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finicom\naid: finicom\nurl: https://finicom.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Multiple trial accounts\n  text: Creating multiple accounts or organizations to obtain additional Trials is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Create an account or post any content if you are not over 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/finicom/eligibility/finicom-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Finicom's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Automation
- Data Sync
- BusinessTools
- Integration
---
