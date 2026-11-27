---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: persons under the age of 18 (eighteen) years
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Failure to successfully comple te suc h verifica tion requirements may result in denial, suspension or restriction of acce ss to the Service s.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Curefit
provenance_date: '2026-11-09'
provider_name: Curefit
provider_slug: curefit
slug: curefit-eligibility
source_date: '2026-11-09'
source_filename: curefit-eligibility.yml
source_heading: Eligibility
source_page: https://static.cult.fit/terms__cult.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curefit\naid: curefit\nurl: https://static.cult.fit/terms__cult.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Failure to successfully comple te suc h verifica tion requirements may result in denial, suspension or restriction\n    of acce ss to the Service s.\nminimum_age:\n  value: '18'\n  text: persons under the age of 18 (eighteen) years\n"
source_yaml_url: https://artifacts.apis.io/curefit/eligibility/curefit-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Curefit's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Fitness
- Wellness
- India
- Company
---
