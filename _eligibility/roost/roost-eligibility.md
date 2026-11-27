---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The System is available in the United States.
  entity_types:
  - text: The System is for your personal, residential, non-commercial use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial residential use only
    text: Unless otherwise specified in your order confirmation, the System is for your personal, residential, non-commercial use only.
  - summary: Not for life safety or emergency purposes
    text: the System is for informational purposes only and it is not intended for life saving, safety, or emergency purposes.
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
name: Roost
provenance_date: '2026-11-10'
provider_name: Roost
provider_slug: roost
slug: roost-eligibility
source_date: '2026-11-10'
source_filename: roost-eligibility.yml
source_heading: Eligibility
source_page: https://getroost.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roost\naid: roost\nurl: https://getroost.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The System is available in the United States.\nentity_types:\n- type: individual\n  text: The System is for your personal, residential, non-commercial use only.\nrestricted_uses:\n- summary: Non-commercial residential use only\n  text: Unless otherwise specified in your order confirmation, the System is for your personal, residential, non-commercial\n    use only.\n- summary: Not for life safety or emergency purposes\n  text: the System is for informational purposes only and it\
  \ is not intended for life saving, safety, or emergency\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/roost/eligibility/roost-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Roost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Insurance
- Insurtech
- Telematics
- Smart Home
- IoT
- Property Insurance
- Loss Prevention
---
