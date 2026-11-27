---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The App and Services are intended for use only by United States residents. If you are not a United States resident you may not use our App or the Services.
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.
    value: '18'
  restricted_uses:
  - summary: No illegal or internet gambling use of Tilt Checking/Card
    text: You must not use your Tilt Checking or Card for any illegal purpose or internet gambling.
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
name: Tilt
provenance_date: '2026-11-10'
provider_name: Tilt
provider_slug: tilt
slug: tilt-eligibility
source_date: '2026-11-10'
source_filename: tilt-eligibility.yml
source_heading: Eligibility
source_page: https://tilt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tilt\naid: tilt\nurl: https://tilt.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The App and Services are intended for use only by United States residents. If you are not a United States\n    resident you may not use our App or the Services.\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.\nrestricted_uses:\n- summary: No illegal or internet gambling use of Tilt Checking/Card\n  text: You must not use your Tilt Checking or Card for any illegal\
  \ purpose or internet gambling.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Services, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/tilt/eligibility/tilt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tilt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Credit Building
- Lending
- Cash Advance
- Credit Cards
- Personal Finance
- Consumer Finance
---
