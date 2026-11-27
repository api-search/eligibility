---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Velocity Points are only available for Eligible Orders completed within Australia.
  entity_types:
  - text: Velocity Frequent Flyer members (“ Velocity Member ”) who have a me&u account can earn 1 Velocity Point per $5 spent on completed Eligible Orders
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Gift card payments excluded
    text: where the method of payment or part payment is a gift card.
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
name: me&u
provenance_date: '2026-11-10'
provider_name: me&u
provider_slug: meandu
slug: meandu-eligibility
source_date: '2026-11-10'
source_filename: meandu-eligibility.yml
source_heading: Eligibility
source_page: https://www.meandu.com/velocity/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: me&u\naid: meandu\nurl: https://www.meandu.com/velocity/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Velocity Points are only available for Eligible Orders completed within Australia.\nentity_types:\n- type: individual\n  text: Velocity Frequent Flyer members (“ Velocity Member ”) who have a me&u account can earn 1 Velocity Point\n    per $5 spent on completed Eligible Orders\nrestricted_uses:\n- summary: Gift card payments excluded\n  text: where the method of payment or part payment is a gift card.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/meandu/eligibility/meandu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from me&u's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hospitality
- Software-as-a-Service
- Payments
- Reservations
---
