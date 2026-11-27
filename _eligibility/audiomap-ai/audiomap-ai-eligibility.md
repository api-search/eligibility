---
api_specs:
- filename: audiomap-ai-ask-api-openapi.yml
  format: yaml
  label: AudioMap Ask API
  slug: audiomap-ai-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-ask-api-openapi.yml
- filename: audiomap-ai-content-api-openapi.yml
  format: yaml
  label: AudioMap Content API
  slug: audiomap-ai-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-content-api-openapi.yml
- filename: audiomap-ai-deliverables-api-openapi.yml
  format: yaml
  label: AudioMap Deliverables API
  slug: audiomap-ai-deliverables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-deliverables-api-openapi.yml
- filename: audiomap-ai-notes-api-openapi.yml
  format: yaml
  label: AudioMap Notes API
  slug: audiomap-ai-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-notes-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Si eres consumidor, serán competentes los juzgados y tribunales que la ley determine como fuero imperativo (en general, los de tu domicilio)
    type: individual
  - text: Si eres una empresa o un profesional, las partes se someten a los juzgados y tribunales de Málaga
    type: business
  minimum_age:
    text: Debes tener al menos 16 años para usar AudioMap.
    value: '16'
  restricted_uses:
  - summary: Recording without consent or for illegal purposes
    text: No uses AudioMap para grabar a alguien sin su conocimiento, con fines ilegales, ni para procesar contenido prohibido (incitación al odio, abuso, actividad ilícita).
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
name: AudioMap
provenance_date: '2026-11-09'
provider_name: AudioMap
provider_slug: audiomap-ai
slug: audiomap-ai-eligibility
source_date: '2026-11-09'
source_filename: audiomap-ai-eligibility.yml
source_heading: Eligibility
source_page: https://audiomap.ai/es/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AudioMap\naid: audiomap-ai\nurl: https://audiomap.ai/es/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Si eres consumidor, serán competentes los juzgados y tribunales que la ley determine como fuero imperativo\n    (en general, los de tu domicilio)\n- type: business\n  text: Si eres una empresa o un profesional, las partes se someten a los juzgados y tribunales de Málaga\nrestricted_uses:\n- summary: Recording without consent or for illegal purposes\n  text: No uses AudioMap para grabar a alguien sin su conocimiento, con fines\
  \ ilegales, ni para procesar contenido\n    prohibido (incitación al odio, abuso, actividad ilícita).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Debes tener al menos 16 años para usar AudioMap.\n"
source_yaml_url: https://artifacts.apis.io/audiomap-ai/eligibility/audiomap-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AudioMap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Transcription
- Audio
- Meeting Notes
- Europe
---
