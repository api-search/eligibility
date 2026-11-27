---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are an individual (i.e., not a corporation) and you are of legal age to form a binding contract or have your parent’s permission to do so
    type: individual
  minimum_age:
    text: you are at least 16 years or age or older
    value: '16'
  restricted_uses:
  - summary: Commercial activity without consent
    text: involves commercial activities and/or sales without Company’s prior written consent such as contests, sweepstakes, barter, advertising, or pyramid schemes
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
name: Vungle
provenance_date: '2026-11-10'
provider_name: Vungle
provider_slug: vungle
slug: vungle-eligibility
source_date: '2026-11-10'
source_filename: vungle-eligibility.yml
source_heading: Eligibility
source_page: https://liftoff.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vungle\naid: vungle\nurl: https://liftoff.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are an individual (i.e., not a corporation) and you are of legal age to form a binding contract or have\n    your parent’s permission to do so\nrestricted_uses:\n- summary: Commercial activity without consent\n  text: involves commercial activities and/or sales without Company’s prior written consent such as contests, sweepstakes,\n    barter, advertising, or pyramid schemes\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are at least 16 years or age or older\n"
source_yaml_url: https://artifacts.apis.io/vungle/eligibility/vungle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Vungle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Mobile
- Monetization
- User Acquisition
- AdTech
- Analytics
- Reporting
---
