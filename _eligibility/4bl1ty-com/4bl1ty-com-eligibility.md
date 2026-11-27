---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: des entreprises ayant besoin de prestations humaines
    type: business
  - text: des personnes physiques disponibles pour réaliser ces missions
    type: individual
  minimum_age:
    text: L'inscription est réservée aux personnes âgées de 15 ans minimum
    value: '15'
  restricted_uses:
  - summary: Identity impersonation prohibited
    text: L'utilisateur s'engage à ne pas usurper l'identité d'un tiers.
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
name: 4bl1ty
provenance_date: '2026-11-09'
provider_name: 4bl1ty
provider_slug: 4bl1ty-com
slug: 4bl1ty-com-eligibility
source_date: '2026-11-09'
source_filename: 4bl1ty-com-eligibility.yml
source_heading: Eligibility
source_page: https://4bl1ty.com/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 4bl1ty\naid: 4bl1ty-com\nurl: https://4bl1ty.com/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: des entreprises ayant besoin de prestations humaines\n- type: individual\n  text: des personnes physiques disponibles pour réaliser ces missions\nrestricted_uses:\n- summary: Identity impersonation prohibited\n  text: L'utilisateur s'engage à ne pas usurper l'identité d'un tiers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '15'\n  text: L'inscription est réservée aux personnes\
  \ âgées de 15 ans minimum\n"
source_yaml_url: https://artifacts.apis.io/4bl1ty-com/eligibility/4bl1ty-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 4bl1ty's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- Artificial Intelligence
- Human-in-the-Loop
- Task Automation
- France
---
