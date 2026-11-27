---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you must be, and represent and warrant that you are, at least 13 years of age and competent to agree to these User Terms
    value: '13'
  restricted_uses:
  - summary: No sensitive personal data without consent
    text: contains any sensitive personal information, such as financial information, payment card numbers, social security numbers, or health information without Archipelago’s prior written consent granted as part of a Customer Agreement
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
name: Archipelago
provenance_date: '2026-11-09'
provider_name: Archipelago
provider_slug: archipelago
slug: archipelago-eligibility
source_date: '2026-11-09'
source_filename: archipelago-eligibility.yml
source_heading: Eligibility
source_page: https://www.onarchipelago.com/user-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Archipelago\naid: archipelago\nurl: https://www.onarchipelago.com/user-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sensitive personal data without consent\n  text: contains any sensitive personal information, such as financial information, payment card numbers, social\n    security numbers, or health information without Archipelago’s prior written consent granted as part of a Customer\n    Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '13'\n  text: you must be, and represent and warrant that you are, at least 13 years of age and competent to agree to\n    these User Terms\n"
source_yaml_url: https://artifacts.apis.io/archipelago/eligibility/archipelago-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Archipelago's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Property Risk
- Underwriting
- Risk Management
- Commercial Property
- GraphQL
- Data
- AI Agents
---
