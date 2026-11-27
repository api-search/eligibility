---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Debe tener la capacidad legal y la autoridad para aceptar estos Términos en nombre de su empresa.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use or spam
    text: No puede usar el Servicio de forma ilícita, para enviar spam, ni de ninguna manera que infrinja derechos o viole la ley aplicable.
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
name: Axamer
provenance_date: '2026-11-09'
provider_name: Axamer
provider_slug: axamer
slug: axamer-eligibility
source_date: '2026-11-09'
source_filename: axamer-eligibility.yml
source_heading: Eligibility
source_page: https://menteo.ai/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Axamer\naid: axamer\nurl: https://menteo.ai/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Debe tener la capacidad legal y la autoridad para aceptar estos Términos en nombre de su empresa.\nrestricted_uses:\n- summary: Unlawful use or spam\n  text: No puede usar el Servicio de forma ilícita, para enviar spam, ni de ninguna manera que infrinja derechos\n    o viole la ley aplicable.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/axamer/eligibility/axamer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Axamer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Restaurant
- Food Service
- Customer Engagement
- Loyalty
- Messaging
- WhatsApp
- Latin America
- Software-as-a-Service
---
