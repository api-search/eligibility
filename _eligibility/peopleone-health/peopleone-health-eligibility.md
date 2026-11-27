---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All references on the Website or the Application to information, materials, products and services apply to information, materials, products and services available in the United States, unless otherwise stated.
  entity_types:
  - text: you certify that you are at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: you certify that you are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Not a substitute for medical treatment
    text: THE WEBSITE, THE APPLICATION, THE SERVICES, AND ANY AND ALL CONTENT ARE NOT SUBSTITUTES FOR, AND SHOULD NEVER BE USED IN LIEU OF, MEDICAL TREATMENT AND EVALUATION BY A LICENSED PHYSICIAN.
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
name: PeopleOne Health
provenance_date: '2026-11-10'
provider_name: PeopleOne Health
provider_slug: peopleone-health
slug: peopleone-health-eligibility
source_date: '2026-11-10'
source_filename: peopleone-health-eligibility.yml
source_heading: Eligibility
source_page: https://peopleonehealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PeopleOne Health\naid: peopleone-health\nurl: https://peopleonehealth.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: All references on the Website or the Application to information, materials, products and services apply\n    to information, materials, products and services available in the United States, unless otherwise stated.\nentity_types:\n- type: individual\n  text: you certify that you are at least eighteen (18) years of age.\nrestricted_uses:\n- summary: Not a substitute for medical treatment\n  text: THE WEBSITE, THE APPLICATION, THE\
  \ SERVICES, AND ANY AND ALL CONTENT ARE NOT SUBSTITUTES FOR, AND SHOULD\n    NEVER BE USED IN LIEU OF, MEDICAL TREATMENT AND EVALUATION BY A LICENSED PHYSICIAN.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you certify that you are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/peopleone-health/eligibility/peopleone-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from PeopleOne Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Primary Care
- Value-Based Care
- Employer Benefits
- Digital Health
---
