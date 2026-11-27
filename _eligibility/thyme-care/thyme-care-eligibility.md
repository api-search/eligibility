---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for use in the United States of America only.
  minimum_age:
    text: You are at least eighteen (18) years old, and (b) all required Account Information submitted during registration
    value: '18'
  restricted_uses:
  - summary: Emergency use
    text: IN THE EVENT OF A MEDICAL EMERGENCY, USERS SHOULD CALL 911 OR CONTACT THEIR PRIMARY HEALTH PROVIDER.
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
name: Thyme Care
provenance_date: '2026-11-10'
provider_name: Thyme Care
provider_slug: thyme-care
slug: thyme-care-eligibility
source_date: '2026-11-10'
source_filename: thyme-care-eligibility.yml
source_heading: Eligibility
source_page: https://www.thymecare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thyme Care\naid: thyme-care\nurl: https://www.thymecare.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for use in the United States of America only.\nentity_types: []\nrestricted_uses:\n- summary: Emergency use\n  text: IN THE EVENT OF A MEDICAL EMERGENCY, USERS SHOULD CALL 911 OR CONTACT THEIR PRIMARY HEALTH PROVIDER.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years old, and (b) all required Account Information submitted during registration\n"
source_yaml_url: https://artifacts.apis.io/thyme-care/eligibility/thyme-care-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Thyme Care's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Cancer Care
- Care Navigation
- Value-Based Care
- Digital Health
- Health Services
---
