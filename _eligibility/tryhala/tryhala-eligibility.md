---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Hala AI provides AI-powered voice and text agent software and related services for business use
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Fraudulent or deceptive purposes
    text: Use the service for fraudulent or deceptive purposes
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
name: Hala
provenance_date: '2026-11-10'
provider_name: Hala
provider_slug: tryhala
slug: tryhala-eligibility
source_date: '2026-11-10'
source_filename: tryhala-eligibility.yml
source_heading: Eligibility
source_page: https://tryhala.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hala\naid: tryhala\nurl: https://tryhala.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Hala AI provides AI-powered voice and text agent software and related services for business use\nrestricted_uses:\n- summary: Fraudulent or deceptive purposes\n  text: Use the service for fraudulent or deceptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/tryhala/eligibility/tryhala-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hala's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice Assistant
- Payments
- Small Business
---
