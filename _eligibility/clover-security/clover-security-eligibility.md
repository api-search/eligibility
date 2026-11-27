---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged eighteen (18) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged eighteen (18) years or older.
    value: '18'
  restricted_uses:
  - summary: Competitive use of Site
    text: (j) use the Site for competitive purposes, and/or on behalf of any person or entity that competes with the activities, services, or products offered by Clover
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
name: Clover Security
provenance_date: '2026-11-09'
provider_name: Clover Security
provider_slug: clover-security
slug: clover-security-eligibility
source_date: '2026-11-09'
source_filename: clover-security-eligibility.yml
source_heading: Eligibility
source_page: https://clover.security/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clover Security\naid: clover-security\nurl: https://clover.security/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\nrestricted_uses:\n- summary: Competitive use of Site\n  text: (j) use the Site for competitive purposes, and/or on behalf of any person or entity that competes with the\n    activities, services, or products offered by Clover\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/clover-security/eligibility/clover-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Clover Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Product Security
- Application Security
- Artificial Intelligence
- DevSecOps
- Threat Modeling
---
