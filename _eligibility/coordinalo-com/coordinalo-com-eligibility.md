---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CL
    text: diseñada para profesionales de servicios en Chile que necesitan gestionar citas, agendas y clientes de manera eficiente.
  entity_types:
  - text: Si creas una cuenta para una organización, representas y garantizas que tienes autoridad para vincular esa organización a estos términos.
    type: business
  minimum_age:
    text: Debes tener al menos 18 años de edad o tener el consentimiento de un padre o tutor legal para usar Coordinalo.
    value: '18'
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
name: Coordínalo
provenance_date: '2026-11-09'
provider_name: Coordínalo
provider_slug: coordinalo-com
slug: coordinalo-com-eligibility
source_date: '2026-11-09'
source_filename: coordinalo-com-eligibility.yml
source_heading: Eligibility
source_page: https://coordinalo.com/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coordínalo\naid: coordinalo-com\nurl: https://coordinalo.com/terminos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CL\n  excluded: []\n  text: diseñada para profesionales de servicios en Chile que necesitan gestionar citas, agendas y clientes de manera\n    eficiente.\nentity_types:\n- type: business\n  text: Si creas una cuenta para una organización, representas y garantizas que tienes autoridad para vincular esa\n    organización a estos términos.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Debes tener\
  \ al menos 18 años de edad o tener el consentimiento de un padre o tutor legal para usar Coordinalo.\n"
source_yaml_url: https://artifacts.apis.io/coordinalo-com/eligibility/coordinalo-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Coordínalo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Practice Management
- Healthcare
- Scheduling
- Booking
- Payments
- MCP
- Chile
---
