---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for business customers only.
    type: business
  - text: They are not offered to consumers.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: You represent that you are not located in, organised under the laws of, or controlled by any person or entity that is the subject of sanctions imposed by the European Union, Germany, the United Kingdom, or the United States
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
name: Vanilla Steel
provenance_date: '2026-11-10'
provider_name: Vanilla Steel
provider_slug: vanilla-steel
slug: vanilla-steel-eligibility
source_date: '2026-11-10'
source_filename: vanilla-steel-eligibility.yml
source_heading: Eligibility
source_page: https://vanillasteel.com/software/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vanilla Steel\naid: vanilla-steel\nurl: https://vanillasteel.com/software/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for business customers only.\n- type: individual\n  text: They are not offered to consumers.\nrestricted_uses:\n- summary: Sanctioned persons\n  text: You represent that you are not located in, organised under the laws of, or controlled by any person or entity\n    that is the subject of sanctions imposed by the European Union, Germany, the United Kingdom, or the United States\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vanilla-steel/eligibility/vanilla-steel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Vanilla Steel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Steel
- Metals
- Marketplace
- Trading
- B2B
- Procurement
- RFQ
- Logistics
---
