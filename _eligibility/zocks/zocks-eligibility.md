---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you and the entity that you represent ( “Subscriber” ) is unconditionally consenting to be bound by and is becoming a party to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PHI without business associate agreement
    text: Subscriber shall not provide, upload, distribute or otherwise make available any protected health information in the absence of any such business associate agreement.
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
name: Zocks
provenance_date: '2026-11-10'
provider_name: Zocks
provider_slug: zocks
slug: zocks-eligibility
source_date: '2026-11-10'
source_filename: zocks-eligibility.yml
source_heading: Eligibility
source_page: https://www.zocks.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zocks\naid: zocks\nurl: https://www.zocks.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you and the entity that you represent ( “Subscriber” ) is unconditionally consenting to be bound by and\n    is becoming a party to this Agreement\nrestricted_uses:\n- summary: No PHI without business associate agreement\n  text: Subscriber shall not provide, upload, distribute or otherwise make available any protected health information\n    in the absence of any such business associate agreement.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zocks/eligibility/zocks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Zocks's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- WealthTech
- Financial Advisors
- Artificial Intelligence
- MCP
- Meeting Intelligence
- CRM
---
