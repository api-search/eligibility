---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age; you have the legal capacity to enter into a binding contract
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal activities
    text: you agree that you shall not, nor cause any third party to, use the Site or a Service to perform any illegal activities.
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
name: Eversettled
provenance_date: '2026-11-09'
provider_name: Eversettled
provider_slug: eversettled
slug: eversettled-eligibility
source_date: '2026-11-09'
source_filename: eversettled-eligibility.yml
source_heading: Eligibility
source_page: https://www.eversettled.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eversettled\naid: eversettled\nurl: https://www.eversettled.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age; you have the legal capacity to enter into a binding contract\nrestricted_uses:\n- summary: Illegal activities\n  text: you agree that you shall not, nor cause any third party to, use the Site or a Service to perform any illegal\n    activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18\
  \ years of age\n"
source_yaml_url: https://artifacts.apis.io/eversettled/eligibility/eversettled-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Eversettled's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Estate Settlement
- Probate
- Estate Planning
- Legal Tech
- Fintech
- AI Assistant
- Consumer
---
