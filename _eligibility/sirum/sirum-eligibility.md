---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: use the SIRUM Site if You are under the age of 18 years old
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: use the SIRUM Site for any commercial use, it being understood that the SIRUM Site is for personal, non-commercial use only
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
name: Sirum
provenance_date: '2026-11-10'
provider_name: Sirum
provider_slug: sirum
slug: sirum-eligibility
source_date: '2026-11-10'
source_filename: sirum-eligibility.yml
source_heading: Eligibility
source_page: https://sirum.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sirum\naid: sirum\nurl: https://sirum.org/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: use the SIRUM Site for any commercial use, it being understood that the SIRUM Site is for personal, non-commercial\n    use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: use the SIRUM Site if You are under the age of 18 years old\n"
source_yaml_url: https://artifacts.apis.io/sirum/eligibility/sirum-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Sirum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medication
- Prescription Access
- Non-Profit
- Pharmacy
- Social Impact
---
