---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: bank holidays in the country your Property is in (England, Wales or Scotland)
  entity_types:
  - text: You’re 18 or over (or 16 if you live in Scotland).
    type: individual
  minimum_age:
    text: You’re 18 or over (or 16 if you live in Scotland).
    value: '18'
  restricted_uses:
  - summary: Domestic purposes only
    text: You’ll use the supply for domestic purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Before we agree to take on your supply, and sometimes during your Contract, we’ll carry out a credit check on you.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OVO Energy
provenance_date: '2026-11-10'
provider_name: OVO Energy
provider_slug: ovo-energy
slug: ovo-energy-eligibility
source_date: '2026-11-10'
source_filename: ovo-energy-eligibility.yml
source_heading: Eligibility
source_page: https://www.ovoenergy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OVO Energy\naid: ovo-energy\nurl: https://www.ovoenergy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: bank holidays in the country your Property is in (England, Wales or Scotland)\nentity_types:\n- type: individual\n  text: You’re 18 or over (or 16 if you live in Scotland).\nrestricted_uses:\n- summary: Domestic purposes only\n  text: You’ll use the supply for domestic purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Before we agree to take on your supply, and sometimes during your Contract, we’ll carry out\
  \ a credit check\n    on you.\nminimum_age:\n  value: '18'\n  text: You’re 18 or over (or 16 if you live in Scotland).\n"
source_yaml_url: https://artifacts.apis.io/ovo-energy/eligibility/ovo-energy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from OVO Energy's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Smart Metering
- Energy Retail
- Solar
- EV Charging
- Demand Response
---
