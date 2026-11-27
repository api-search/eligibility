---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    text: Terms distinguish US users and UK/ EU users and Non-US Users; no country exclusions are stated.
  minimum_age:
    text: certify that you are (i) over the age of eighteen (18) (for UK/ EU users), or have the legal ability to consent to the Services or have your Parent/Guardian consent to the Services (for US users)
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: DO NOT USE THIS SERVICE FOR EMERGENCY MEDICAL NEEDS.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access the Services, you must first enroll to establish an individual user account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Talkspace
provenance_date: '2026-11-10'
provider_name: Talkspace
provider_slug: talkspace
slug: talkspace-eligibility
source_date: '2026-11-10'
source_filename: talkspace-eligibility.yml
source_heading: Eligibility
source_page: https://www.talkspace.com/public/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talkspace\naid: talkspace\nurl: https://www.talkspace.com/public/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  excluded: []\n  text: Terms distinguish US users and UK/ EU users and Non-US Users; no country exclusions are stated.\nentity_types: []\nrestricted_uses:\n- summary: Not for emergencies\n  text: DO NOT USE THIS SERVICE FOR EMERGENCY MEDICAL NEEDS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access the Services, you must first enroll to establish an individual user account\nminimum_age:\n  value: '18'\n  text: certify that you are (i) over\
  \ the age of eighteen (18) (for UK/ EU users), or have the legal ability to\n    consent to the Services or have your Parent/Guardian consent to the Services (for US users)\n"
source_yaml_url: https://artifacts.apis.io/talkspace/eligibility/talkspace-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Talkspace's own page on 2026-11-10.
synthetic: false
tags:
- Behavioral Health
- Mental Health
- Online Therapy
- Telehealth
- Psychiatry
- Medication Management
- Teen Therapy
- Couples Therapy
- Employee Assistance
- Health Insurance
- HIPAA
- Public Company
---
