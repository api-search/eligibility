---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: Use the service for lawful purposes only.
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
name: Real Estate Institute of Australia
provenance_date: '2026-11-10'
provider_name: Real Estate Institute of Australia
provider_slug: reia
slug: reia-eligibility
source_date: '2026-11-10'
source_filename: reia-eligibility.yml
source_heading: Eligibility
source_page: https://www.reia.com.au/create-account
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Real Estate Institute of Australia\naid: reia\nurl: https://www.reia.com.au/create-account\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: Use the service for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/reia/eligibility/reia-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Real Estate Institute of Australia's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Australia
- Industry Body
- Standards
- Membership
- Property Data
- Housing Affordability
- Research
- Advocacy
- Rentals
- PropTech
---
