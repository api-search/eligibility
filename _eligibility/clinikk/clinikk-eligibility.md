---
claim_count: 2
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
  - summary: Proxy attendance prohibited
    text: No third party (including family members, friends, or agents) may attend consultations, describe symptoms, or request medical advice on behalf of a Member who is not present.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Membership is activated only after completing our onboarding and evaluation process, which includes a health consultation and may include medical tests. Membership activation is subject to clinical review and eligibility approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clinikk
provenance_date: '2026-11-09'
provider_name: Clinikk
provider_slug: clinikk
slug: clinikk-eligibility
source_date: '2026-11-09'
source_filename: clinikk-eligibility.yml
source_heading: Eligibility
source_page: https://clinikk.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clinikk\naid: clinikk\nurl: https://clinikk.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Proxy attendance prohibited\n  text: No third party (including family members, friends, or agents) may attend consultations, describe symptoms,\n    or request medical advice on behalf of a Member who is not present.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Membership is activated only after completing our onboarding and evaluation process, which includes a health\n    consultation\
  \ and may include medical tests. Membership activation is subject to clinical review and eligibility\n    approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clinikk/eligibility/clinikk-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Clinikk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Health Insurance
- Telehealth
- Membership
- India
---
