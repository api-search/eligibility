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
  - summary: Spam, illegal or policy-violating use
    text: No se permite usar Atendio para enviar spam, contenido ilegal, engañoso o que infrinja las políticas de WhatsApp/Meta.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'El acceso es gestionado: btodigital crea las cuentas de sus clientes.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atendio
provenance_date: '2026-11-09'
provider_name: Atendio
provider_slug: atendio-co
slug: atendio-co-eligibility
source_date: '2026-11-09'
source_filename: atendio-co-eligibility.yml
source_heading: Eligibility
source_page: https://atendio.co/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atendio\naid: atendio-co\nurl: https://atendio.co/terminos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spam, illegal or policy-violating use\n  text: No se permite usar Atendio para enviar spam, contenido ilegal, engañoso o que infrinja las políticas de\n    WhatsApp/Meta.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'El acceso es gestionado: btodigital crea las cuentas de sus clientes.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atendio-co/eligibility/atendio-co-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Atendio's own page on 2026-11-09.
synthetic: false
tags:
- WhatsApp
- Artificial Intelligence
- Chatbots
- Business
- Latin America
- Colombia
---
