---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use our Services, with or without registering. In addition, if you are under 18 years old, you may use our Services, with or without registering, only with the approval of your parent or guardian.
    value: '13'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: You may not utilize the Services for any illegal or fraudulent purposes.
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
name: Dialup
provenance_date: '2026-11-09'
provider_name: Dialup
provider_slug: dialup
slug: dialup-eligibility
source_date: '2026-11-09'
source_filename: dialup-eligibility.yml
source_heading: Eligibility
source_page: https://dialup.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dialup\naid: dialup\nurl: https://dialup.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: You may not utilize the Services for any illegal or fraudulent purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use our Services, with or without registering.\n    In addition, if you are under 18 years old, you may use our Services, with or without registering,\
  \ only with\n    the approval of your parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/dialup/eligibility/dialup-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Dialup's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice
- Social
- Communications
- Consumer App
- Telephony
- Community
---
