---
api_specs:
- filename: ai-tv-openapi-generated.yml
  format: yaml
  label: AI.TV API
  slug: ai-tv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-tv/openapi/_ae-authored/ai-tv-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least thirteen years old, or the minimum age of digital consent in your jurisdiction, to use the Service.
    type: individual
  minimum_age:
    text: You must be at least thirteen years old, or the minimum age of digital consent in your jurisdiction, to use the Service.
    value: '13'
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Service only for lawful and responsible purposes.
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
name: AI.TV
provenance_date: '2026-11-09'
provider_name: AI.TV
provider_slug: ai-tv
slug: ai-tv-eligibility
source_date: '2026-11-09'
source_filename: ai-tv-eligibility.yml
source_heading: Eligibility
source_page: https://ai.tv/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI.TV\naid: ai-tv\nurl: https://ai.tv/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least thirteen years old, or the minimum age of digital consent in your jurisdiction, to\n    use the Service.\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Service only for lawful and responsible purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least thirteen years old, or the minimum age of digital consent\
  \ in your jurisdiction, to\n    use the Service.\n"
source_yaml_url: https://artifacts.apis.io/ai-tv/eligibility/ai-tv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AI.TV's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Streaming
- Entertainment
- AI-Generated
---
