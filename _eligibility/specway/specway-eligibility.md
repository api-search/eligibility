---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Service, you represent that you are at least 18 years of age and have the legal capacity to enter into these Terms.
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent purposes
    text: Use the Service for illegal or fraudulent purposes
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
name: Specway
provenance_date: '2026-11-10'
provider_name: Specway
provider_slug: specway
slug: specway-eligibility
source_date: '2026-11-10'
source_filename: specway-eligibility.yml
source_heading: Eligibility
source_page: https://specway.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Specway\naid: specway\nurl: https://specway.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Service, you represent that you are at least 18 years of age and have the legal capacity to\n    enter into these Terms.\nrestricted_uses:\n- summary: Illegal or fraudulent purposes\n  text: Use the Service for illegal or fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/specway/eligibility/specway-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Specway's own page on 2026-11-10.
synthetic: false
tags:
- API Documentation
- Developer Tools
- AI Integration
- Interactive Docs
- OpenAPI
---
