---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: clients personnes physiques
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Private use only
    text: Lorsqu'il utilise la Plateforme, l'Utilisateur déclare agir à titre privé.
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
name: Happytal
provenance_date: '2026-11-09'
provider_name: Happytal
provider_slug: happytal
slug: happytal-eligibility
source_date: '2026-11-09'
source_filename: happytal-eligibility.yml
source_heading: Eligibility
source_page: https://www.happytal.com/legal/cgu-marketplace
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Happytal\naid: happytal\nurl: https://www.happytal.com/legal/cgu-marketplace\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: clients personnes physiques\nrestricted_uses:\n- summary: Private use only\n  text: Lorsqu'il utilise la Plateforme, l'Utilisateur déclare agir à titre privé.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/happytal/eligibility/happytal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Happytal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Healthcare
- Health
- France
- Concierge
- Marketplace
- Elder Care
- Patient Experience
- Health Tech
---
