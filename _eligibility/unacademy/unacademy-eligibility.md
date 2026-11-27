---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a resident of India or any other country (except USA, UK or EU countries), then you must have attained at least 18 (eighteen) years of age to register and use the Unacademy Platform
  minimum_age:
    text: If you are a resident of the United States of America (USA) or United Kingdom (UK) and have attained at least 13 (thirteen) years of age, then you can register and use the Unacademy Platform.
    value: 18 (varies by region)
  restricted_uses:
  - summary: Commercial use requires prior written approval
    text: You agree not to use the Platform for any of the following commercial uses unless you obtain Unacademy’s prior written approval
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we reserve the right to reject or put on-hold your registration on the Platform as may be required to comply with any legal and regulatory provisions
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unacademy
provenance_date: '2026-11-10'
provider_name: Unacademy
provider_slug: unacademy
slug: unacademy-eligibility
source_date: '2026-11-10'
source_filename: unacademy-eligibility.yml
source_heading: Eligibility
source_page: https://unacademy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unacademy\naid: unacademy\nurl: https://unacademy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you are a resident of India or any other country (except USA, UK or EU countries), then you must have\n    attained at least 18 (eighteen) years of age to register and use the Unacademy Platform\nentity_types: []\nrestricted_uses:\n- summary: Commercial use requires prior written approval\n  text: You agree not to use the Platform for any of the following commercial uses unless you obtain Unacademy’s\n    prior written approval\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: we reserve the right to reject or put on-hold your registration on the Platform as may be required to comply\n    with any legal and regulatory provisions\nminimum_age:\n  value: 18 (varies by region)\n  text: If you are a resident of the United States of America (USA) or United Kingdom (UK) and have attained at\n    least 13 (thirteen) years of age, then you can register and use the Unacademy Platform.\n"
source_yaml_url: https://artifacts.apis.io/unacademy/eligibility/unacademy-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Unacademy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EdTech
- Education
- Learning
- Exam Preparation
- Courses
- India
---
