---
api_specs:
- filename: corpusiuris-mx-agent-api-openapi.yml
  format: yaml
  label: Corpus Iuris Agent API
  slug: corpusiuris-mx-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiuris-mx/openapi/corpusiuris-mx-agent-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Cada conexión y token están vinculados a una única persona física titular de la cuenta.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Asesoría en otras jurisdicciones
    text: Utilizar la plataforma para asesorar a clientes en jurisdicciones distintas a la mexicana sin verificar la aplicabilidad del derecho consultado a esa jurisdicción.
  - summary: Uso comercial de volumen o integración
    text: El uso comercial de volumen o la integración en productos requiere un convenio separado
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Para utilizar el servicio el usuario debe registrarse mediante una cuenta de Google válida.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Corpus Iuris
provenance_date: '2026-11-09'
provider_name: Corpus Iuris
provider_slug: corpusiuris-mx
slug: corpusiuris-mx-eligibility
source_date: '2026-11-09'
source_filename: corpusiuris-mx-eligibility.yml
source_heading: Eligibility
source_page: https://corpusiuris.mx/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corpus Iuris\naid: corpusiuris-mx\nurl: https://corpusiuris.mx/terminos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Cada conexión y token están vinculados a una única persona física titular de la cuenta.\nrestricted_uses:\n- summary: Asesoría en otras jurisdicciones\n  text: Utilizar la plataforma para asesorar a clientes en jurisdicciones distintas a la mexicana sin verificar\n    la aplicabilidad del derecho consultado a esa jurisdicción.\n- summary: Uso comercial de volumen o integración\n  text: El uso comercial de volumen\
  \ o la integración en productos requiere un convenio separado\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Para utilizar el servicio el usuario debe registrarse mediante una cuenta de Google válida.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corpusiuris-mx/eligibility/corpusiuris-mx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Corpus Iuris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Research
- Artificial Intelligence
- Mexico
- Jurisprudence
- MCP
- Search
---
