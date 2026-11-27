---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Angle Health is licensed to underwrite health coverage in the state of Utah only
  minimum_age:
    text: All website users ("you", "your" and "they") represent and warrant that they are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: The content of this website is provided as general information only and is not medical, legal, or health plan purchasing advice.
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
name: Angle Health
provenance_date: '2026-11-09'
provider_name: Angle Health
provider_slug: angle-health
slug: angle-health-eligibility
source_date: '2026-11-09'
source_filename: angle-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.anglehealth.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Angle Health\naid: angle-health\nurl: https://www.anglehealth.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Angle Health is licensed to underwrite health coverage in the state of Utah only\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: The content of this website is provided as general information only and is not medical, legal, or health\n    plan purchasing advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All website users (\"you\", \"your\" and \"\
  they\") represent and warrant that they are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/angle-health/eligibility/angle-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Angle Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Insurance
- Insurance
- Insurtech
- Employee Benefits
- Healthcare
- Quoting
- Health
- API Platform
---
