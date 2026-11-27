---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you (a) are not identified on the Office of Foreign Assets Control's Specially Designated Nationals List
  entity_types:
  - text: You must be at least 13 years of age to access and use the Services. There is no exception to this requirement.
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to access and use the Services. There is no exception to this requirement.
    value: '13'
  restricted_uses:
  - summary: Violating export control laws
    text: you agree to abide by any applicable export control laws and not to transfer, by electronic transmission or otherwise, any UGC, software or other materials subject to restrictions under such laws to a national destination prohibited by such laws
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
name: ForeVR
provenance_date: '2026-11-09'
provider_name: ForeVR
provider_slug: forevr
slug: forevr-eligibility
source_date: '2026-11-09'
source_filename: forevr-eligibility.yml
source_heading: Eligibility
source_page: https://www.forevrgames.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ForeVR\naid: forevr\nurl: https://www.forevrgames.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you (a) are not identified on the Office of Foreign Assets Control's Specially\n    Designated Nationals List\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to access and use the Services. There is no exception to this requirement.\nrestricted_uses:\n- summary: Violating export control laws\n  text: you agree to abide by any applicable export control laws and not to transfer, by electronic transmission\n    or otherwise,\
  \ any UGC, software or other materials subject to restrictions under such laws to a national destination\n    prohibited by such laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to access and use the Services. There is no exception to this requirement.\n"
source_yaml_url: https://artifacts.apis.io/forevr/eligibility/forevr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ForeVR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Virtual Reality
- Gaming
- Entertainment
- Meta Quest
- Multiplayer
---
