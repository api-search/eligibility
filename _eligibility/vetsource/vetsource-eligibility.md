---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Use of our Services is currently authorized only in the United States and its territories and possessions (the “Territory”).
  entity_types:
  - text: This Site is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Site is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal use only for purchases
    text: You may only purchase Products for personal use (i.e., use by your pet). The Products are not authorized for resale.
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
name: VetSource
provenance_date: '2026-11-10'
provider_name: VetSource
provider_slug: vetsource
slug: vetsource-eligibility
source_date: '2026-11-10'
source_filename: vetsource-eligibility.yml
source_heading: Eligibility
source_page: https://assets.vetsource.com/m/4b45c75df5bb0014/original/Pet-Owner-Terms-of-Use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VetSource\naid: vetsource\nurl: https://assets.vetsource.com/m/4b45c75df5bb0014/original/Pet-Owner-Terms-of-Use.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Use of our Services is currently authorized only in the United States and its territories and possessions\n    (the “Territory”).\nentity_types:\n- type: individual\n  text: This Site is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Personal use only for purchases\n  text: You may only purchase Products for personal use (i.e., use by your pet). The Products are not\
  \ authorized\n    for resale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Site is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/vetsource/eligibility/vetsource-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from VetSource's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Veterinary
- Pharmacy
- Pet Health
- Practice Management
- Client Engagement
- Data Analytics
---
