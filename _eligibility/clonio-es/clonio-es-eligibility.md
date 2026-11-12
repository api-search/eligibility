---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: La Plataforma está dirigida exclusivamente a profesionales y empresas
    type: business
  minimum_age:
    text: solo pueden utilizarla personas mayores de dieciocho (18) años
    value: '18'
  restricted_uses:
  - summary: Respect AI model red lines
    text: El usuario se obliga asimismo a no superar las líneas rojas técnicas del modelo de inteligencia artificial descritas en las Normas de generación de imágenes.
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
name: Clonio
provenance_date: '2026-11-09'
provider_name: Clonio
provider_slug: clonio-es
slug: clonio-es-eligibility
source_date: '2026-11-09'
source_filename: clonio-es-eligibility.yml
source_heading: Eligibility
source_page: https://clonio.es/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clonio\naid: clonio-es\nurl: https://clonio.es/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: La Plataforma está dirigida exclusivamente a profesionales y empresas\nrestricted_uses:\n- summary: Respect AI model red lines\n  text: El usuario se obliga asimismo a no superar las líneas rojas técnicas del modelo de inteligencia artificial\n    descritas en las Normas de generación de imágenes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: solo pueden utilizarla\
  \ personas mayores de dieciocho (18) años\n"
source_yaml_url: https://artifacts.apis.io/clonio-es/eligibility/clonio-es-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Clonio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LinkedIn
- Content Generation
- Social Media
- Marketing
- Scheduling
- MCP
---
