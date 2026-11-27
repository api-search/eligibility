---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are using the Website for your own personal use and not for commercial purposes
    type: individual
  minimum_age:
    text: you are over 18 years of age
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: you are using the Website for your own personal use and not for commercial purposes
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
name: Reserv
provenance_date: '2026-11-10'
provider_name: Reserv
provider_slug: reserv
slug: reserv-eligibility
source_date: '2026-11-10'
source_filename: reserv-eligibility.yml
source_heading: Eligibility
source_page: https://www.reserv.com/legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reserv\naid: reserv\nurl: https://www.reserv.com/legal-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are using the Website for your own personal use and not for commercial purposes\nrestricted_uses:\n- summary: No commercial use\n  text: you are using the Website for your own personal use and not for commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/reserv/eligibility/reserv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Reserv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Claims Management
- Insurtech
- Third-Party Administrator
- Property and Casualty
- Artificial Intelligence
- Data Analytics
---
