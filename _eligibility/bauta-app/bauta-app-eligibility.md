---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old (or the age of digital consent where you live, if higher) and legally able to enter into these Terms
    type: individual
  - text: where you act for an organization, you confirm you are authorized to bind it.
    type: business
  minimum_age:
    text: You must be at least 16 years old (or the age of digital consent where you live, if higher)
    value: '16'
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
name: Bauta
provenance_date: '2026-11-09'
provider_name: Bauta
provider_slug: bauta-app
slug: bauta-app-eligibility
source_date: '2026-11-09'
source_filename: bauta-app-eligibility.yml
source_heading: Eligibility
source_page: https://bauta.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bauta\naid: bauta-app\nurl: https://bauta.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old (or the age of digital consent where you live, if higher) and legally\n    able to enter into these Terms\n- type: business\n  text: where you act for an organization, you confirm you are authorized to bind it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old (or the age of digital\
  \ consent where you live, if higher)\n"
source_yaml_url: https://artifacts.apis.io/bauta-app/eligibility/bauta-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Bauta's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Sharing
- NoLogin
- Web Links
- Productivity
---
