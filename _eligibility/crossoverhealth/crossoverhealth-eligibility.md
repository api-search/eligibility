---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: representing that you are of sufficient legal age to use or participate in such service or feature
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You agree not to use the Website or any of its features for any purpose that is unlawful or prohibited by the Terms.
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
name: Crossoverhealth
provenance_date: '2026-11-09'
provider_name: Crossoverhealth
provider_slug: crossoverhealth
slug: crossoverhealth-eligibility
source_date: '2026-11-09'
source_filename: crossoverhealth-eligibility.yml
source_heading: Eligibility
source_page: https://crossoverhealth.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crossoverhealth\naid: crossoverhealth\nurl: https://crossoverhealth.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You agree not to use the Website or any of its features for any purpose that is unlawful or prohibited by\n    the Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: representing that you are of sufficient legal age to use or participate in such service or feature\n"
source_yaml_url: https://artifacts.apis.io/crossoverhealth/eligibility/crossoverhealth-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Crossoverhealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Digital Health
- Telehealth
- Employer Health
- Care Navigation
- Occupational Medicine
---
