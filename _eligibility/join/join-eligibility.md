---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Le Client a la qualité de professionnel, entendu comme toute personne physique ou morale agissant à des fins entrant dans le cadre de son activité commerciale, industrielle, artisanale, libérale ou agricole
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: La Société demeure cependant libre de refuser toute demande du Client s’il ne remplit pas les conditions prévues
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Join
provenance_date: '2026-11-09'
provider_name: Join
provider_slug: join
slug: join-eligibility
source_date: '2026-11-09'
source_filename: join-eligibility.yml
source_heading: Eligibility
source_page: https://join-stories.com/conditions-generales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Join\naid: join\nurl: https://join-stories.com/conditions-generales\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Le Client a la qualité de professionnel, entendu comme toute personne physique ou morale agissant à des\n    fins entrant dans le cadre de son activité commerciale, industrielle, artisanale, libérale ou agricole\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: La Société demeure cependant libre de refuser toute demande du Client s’il ne remplit pas les conditions\n    prévues\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/join/eligibility/join-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Join's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Commerce
- E-Commerce
- Shoppable Video
- User Generated Content
- Video Analytics
- AI Video
- Retail
---
