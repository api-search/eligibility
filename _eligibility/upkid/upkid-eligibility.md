---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority where you live) and able to form a binding contract to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Customer applicant data limits
    text: Customers agree to use applicant and provider information only for legitimate hiring or staffing purposes and in compliance with applicable law and Platform policies.
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
name: Upkid
provenance_date: '2026-11-10'
provider_name: Upkid
provider_slug: upkid
slug: upkid-eligibility
source_date: '2026-11-10'
source_filename: upkid-eligibility.yml
source_heading: Eligibility
source_page: https://www.upkid.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upkid\naid: upkid\nurl: https://www.upkid.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Customer applicant data limits\n  text: Customers agree to use applicant and provider information only for legitimate hiring or staffing purposes\n    and in compliance with applicable law and Platform policies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority where you live) and able to form\
  \ a binding\n    contract to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/upkid/eligibility/upkid-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Upkid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Childcare
- Education
- Staffing
- Marketplace
- Hiring
- Early Childhood Education
- Recruiting
- Software-as-a-Service
---
