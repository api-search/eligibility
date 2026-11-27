---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Registration and participation on the Site and the Service is restricted to: individuals over 18 years of age or over;'
    type: individual
  minimum_age:
    text: 'Registration and participation on the Site and the Service is restricted to: individuals over 18 years of age or over; emancipated minors; users under age 18 who possess legal parental or guardian consent; and users under age 13 whose parent or guardian has provided prior verifiable consent to us.'
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct in submissions
    text: Discuss or incite illegal activity.
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
name: Ceregojapaninc
provenance_date: '2026-11-09'
provider_name: Ceregojapaninc
provider_slug: ceregojapaninc
slug: ceregojapaninc-eligibility
source_date: '2026-11-09'
source_filename: ceregojapaninc-eligibility.yml
source_heading: Eligibility
source_page: https://www.cerego.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ceregojapaninc\naid: ceregojapaninc\nurl: https://www.cerego.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Registration and participation on the Site and the Service is restricted to: individuals over 18 years\n    of age or over;'\nrestricted_uses:\n- summary: Prohibited conduct in submissions\n  text: Discuss or incite illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'Registration and participation on the Site and the\
  \ Service is restricted to: individuals over 18 years\n    of age or over; emancipated minors; users under age 18 who possess legal parental or guardian consent; and users\n    under age 13 whose parent or guardian has provided prior verifiable consent to us.'\n"
source_yaml_url: https://artifacts.apis.io/ceregojapaninc/eligibility/ceregojapaninc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ceregojapaninc's own page on 2026-11-09.
synthetic: false
tags:
- EdTech
- Adaptive Learning
- Artificial Intelligence
- Japan
- Education
---
