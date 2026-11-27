---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only use the Services if you are 18 years of age and older, a licensed mental health professional in the jurisdiction(s) in which you provide clinical services
    type: individual
  - text: Practice operates a psychotherapy Practice that furnishes psychotherapy services to the public through independent contractor and/or employed practitioners
    type: business
  minimum_age:
    text: You may only use the Services if you are 18 years of age and older
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In addition, you will need to submit a valid photo ID, evidence of your certifications, and proof of valid and current malpractice insurance (if not submitted on your behalf by your employer).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Journey Clinical
provenance_date: '2026-11-09'
provider_name: Journey Clinical
provider_slug: journey-clinical
slug: journey-clinical-eligibility
source_date: '2026-11-09'
source_filename: journey-clinical-eligibility.yml
source_heading: Eligibility
source_page: https://www.journeyclinical.com/psychotherapist-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Journey Clinical\naid: journey-clinical\nurl: https://www.journeyclinical.com/psychotherapist-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only use the Services if you are 18 years of age and older, a licensed mental health professional\n    in the jurisdiction(s) in which you provide clinical services\n- type: business\n  text: Practice operates a psychotherapy Practice that furnishes psychotherapy services to the public through independent\n    contractor and/or employed practitioners\nrestricted_uses:\
  \ []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In addition, you will need to submit a valid photo ID, evidence of your certifications, and proof of valid\n    and current malpractice insurance (if not submitted on your behalf by your employer).\nminimum_age:\n  value: '18'\n  text: You may only use the Services if you are 18 years of age and older\n"
source_yaml_url: https://artifacts.apis.io/journey-clinical/eligibility/journey-clinical-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Journey Clinical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telehealth
- Mental Health
- Healthcare
- Ketamine-Assisted Psychotherapy
- Medication Management
- HIPAA
- Digital Health
---
