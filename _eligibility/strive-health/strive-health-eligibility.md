---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This Site is intended for adults only. This Site is not intended for any children under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Use in violation of law
    text: You agree to comply with all applicable laws regarding your use of the Site.
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
name: Strive Health
provenance_date: '2026-11-10'
provider_name: Strive Health
provider_slug: strive-health
slug: strive-health-eligibility
source_date: '2026-11-10'
source_filename: strive-health-eligibility.yml
source_heading: Eligibility
source_page: https://strivehealth.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Strive Health\naid: strive-health\nurl: https://strivehealth.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use in violation of law\n  text: You agree to comply with all applicable laws regarding your use of the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Site is intended for adults only. This Site is not intended for any children under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/strive-health/eligibility/strive-health-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Strive Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Kidney Care
- Value-Based Care
- Healthcare
- Machine Learning
- Population Health
---
