---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use of content
    text: sauf celui de consulter les Contenus pour son usage personnel et à des fins non commerciales
  - summary: Compliance with CGU
    text: L’Utilisateur s’engage à utiliser le Site dans le respect des présentes CGU et des dispositions législatives et réglementaires en vigueur.
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
name: Enedis
provenance_date: '2026-11-09'
provider_name: Enedis
provider_slug: enedis
slug: enedis-eligibility
source_date: '2026-11-09'
source_filename: enedis-eligibility.yml
source_heading: Eligibility
source_page: https://www.enedis.fr/mentions-legales-et-conditions-generales-dutilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enedis\naid: enedis\nurl: https://www.enedis.fr/mentions-legales-et-conditions-generales-dutilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use of content\n  text: sauf celui de consulter les Contenus pour son usage personnel et à des fins non commerciales\n- summary: Compliance with CGU\n  text: L’Utilisateur s’engage à utiliser le Site dans le respect des présentes CGU et des dispositions législatives\n    et réglementaires en vigueur.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enedis/eligibility/enedis-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Enedis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Electricity
- Utility
- France
- Public Service
---
