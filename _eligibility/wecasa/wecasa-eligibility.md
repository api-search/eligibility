---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: Partout en France
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Dependent persons excluded
    text: ne pas utiliser les Services de Wecasa au bénéfice de personnes dépendantes.
  - summary: Only at home
    text: ne pas utiliser les Services de Wecasa dans un autre lieu que leur résidence principale ou secondaire
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
name: Wecasa
provenance_date: '2026-11-10'
provider_name: Wecasa
provider_slug: wecasa
slug: wecasa-eligibility
source_date: '2026-11-10'
source_filename: wecasa-eligibility.yml
source_heading: Eligibility
source_page: https://www.wecasa.fr/page/conditions-generales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wecasa\naid: wecasa\nurl: https://www.wecasa.fr/page/conditions-generales\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: Partout en France\nentity_types: []\nrestricted_uses:\n- summary: Dependent persons excluded\n  text: ne pas utiliser les Services de Wecasa au bénéfice de personnes dépendantes.\n- summary: Only at home\n  text: ne pas utiliser les Services de Wecasa dans un autre lieu que leur résidence principale ou secondaire\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wecasa/eligibility/wecasa-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Wecasa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- Home Services
- Beauty and Wellness
- Cleaning
- Childcare
- On-Demand
- France
- Mobile App
---
