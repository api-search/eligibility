---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you choose to register for the Service, you agree to provide and maintain true, accurate, current and complete information about yourself
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering. In addition, if you are under 18 years old, you may use the Service, with or without registering, only with the approval of your parent or guardian.
    value: '13'
  restricted_uses:
  - summary: Under-13 users barred
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
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
name: Outcomes4Me
provenance_date: '2026-11-10'
provider_name: Outcomes4Me
provider_slug: outcomes4me
slug: outcomes4me-eligibility
source_date: '2026-11-10'
source_filename: outcomes4me-eligibility.yml
source_heading: Eligibility
source_page: https://static.outcomes4me.com/termsofservice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outcomes4Me\naid: outcomes4me\nurl: https://static.outcomes4me.com/termsofservice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you choose to register for the Service, you agree to provide and maintain true, accurate, current and\n    complete information about yourself\nrestricted_uses:\n- summary: Under-13 users barred\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n    In addition, if you are under 18 years old, you may use the Service, with or without registering, only with\n    the approval of your parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/outcomes4me/eligibility/outcomes4me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Outcomes4Me's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Healthcare
- Cancer
- Oncology
- Patient Engagement
- Real-World Data
- Clinical Trials
---
