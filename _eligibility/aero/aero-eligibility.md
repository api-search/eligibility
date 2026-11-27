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
  - summary: Multiple accounts for promotions
    text: Opening multiple accounts on the same device for purposes of redeeming a promotion, deal and/or discount code more than once is prohibited
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
name: Aero
provenance_date: '2026-11-09'
provider_name: Aero
provider_slug: aero
slug: aero-eligibility
source_date: '2026-11-09'
source_filename: aero-eligibility.yml
source_heading: Eligibility
source_page: https://aero.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aero\naid: aero\nurl: https://aero.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Multiple accounts for promotions\n  text: Opening multiple accounts on the same device for purposes of redeeming a promotion, deal and/or discount\n    code more than once is prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aero/eligibility/aero-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Air Travel
- Airlines
- Private Aviation
- Transportation
- Booking
- Consumer
- Aviation
---
