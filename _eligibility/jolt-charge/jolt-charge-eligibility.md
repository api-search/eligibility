---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be over 16 to use the Services.
    value: '16'
  restricted_uses:
  - summary: No commercial or business use
    text: not use the Services or the Application in connection with a commercial or business purpose, except those that are specifically endorsed or approved by JOLT
  - summary: Competitors barred
    text: If you are in the business of providing similar Services to JOLT, whether for business users or domestic users, then you are a competitor of JOLT.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide us with an eligible credit/debit card to use the JOLT services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: JOLT
provenance_date: '2026-11-09'
provider_name: JOLT
provider_slug: jolt-charge
slug: jolt-charge-eligibility
source_date: '2026-11-09'
source_filename: jolt-charge-eligibility.yml
source_heading: Eligibility
source_page: https://joltcharge.com/au/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JOLT\naid: jolt-charge\nurl: https://joltcharge.com/au/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No commercial or business use\n  text: not use the Services or the Application in connection with a commercial or business purpose, except those\n    that are specifically endorsed or approved by JOLT\n- summary: Competitors barred\n  text: If you are in the business of providing similar Services to JOLT, whether for business users or domestic\n    users, then you are a competitor of JOLT.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: You must provide us with an eligible credit/debit card to use the JOLT services.\nminimum_age:\n  value: '16'\n  text: You must be over 16 to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/jolt-charge/eligibility/jolt-charge-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from JOLT's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Australia
- EV Charging
- Electricity
- Utilities
- Renewables
- Advertising
- Mobility
- Carbon
- Infrastructure
---
