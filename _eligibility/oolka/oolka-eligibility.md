---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Service provided by Oolka is available and appropriate only for use in India.
  entity_types:
  - text: You have created the User ID for your own personal, non-commercial use
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Money laundering or gambling
    text: disparaging, relating, or encouraging money laundering or gambling
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Upon receipt of your request, Oolka will verify your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Oolka
provenance_date: '2026-11-10'
provider_name: Oolka
provider_slug: oolka
slug: oolka-eligibility
source_date: '2026-11-10'
source_filename: oolka-eligibility.yml
source_heading: Eligibility
source_page: https://oolka.in/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oolka\naid: oolka\nurl: https://oolka.in/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Service provided by Oolka is available and appropriate only for use in India.\nentity_types:\n- type: individual\n  text: You have created the User ID for your own personal, non-commercial use\nrestricted_uses:\n- summary: Money laundering or gambling\n  text: disparaging, relating, or encouraging money laundering or gambling\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Upon receipt of your request, Oolka will verify\
  \ your identity\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/oolka/eligibility/oolka-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Oolka's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit Score
- Credit Building
- Consumer Finance
- Personal Finance
- India
---
