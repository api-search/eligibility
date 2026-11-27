---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: sur le territoire français
  entity_types:
  - text: personne physique disposant de la pleine capacité juridique
    type: individual
  - text: Le Client a la qualité de professionnel , entendu comme toute personne physique ou morale agissant à des fins entrant dans le cadre de son activité commerciale, industrielle, artisanale, libérale ou agricole
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent activity
    text: exercer une activité illégale ou frauduleuse
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
name: Aptimiz
provenance_date: '2026-11-09'
provider_name: Aptimiz
provider_slug: aptimiz
slug: aptimiz-eligibility
source_date: '2026-11-09'
source_filename: aptimiz-eligibility.yml
source_heading: Eligibility
source_page: https://aptimiz.com/cgv/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aptimiz\naid: aptimiz\nurl: https://aptimiz.com/cgv/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: sur le territoire français\nentity_types:\n- type: individual\n  text: personne physique disposant de la pleine capacité juridique\n- type: business\n  text: Le Client a la qualité de professionnel , entendu comme toute personne physique ou morale agissant à des\n    fins entrant dans le cadre de son activité commerciale, industrielle, artisanale, libérale ou agricole\nrestricted_uses:\n- summary: Illegal or fraudulent activity\n  text: exercer une activité illégale ou frauduleuse\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aptimiz/eligibility/aptimiz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Aptimiz's own page on 2026-11-09.
synthetic: false
tags:
- Agriculture
- Farm Management
- Time Tracking
- Connected Devices
- Compliance
---
