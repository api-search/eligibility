---
api_specs:
- filename: audo-ai-api-openapi.json
  format: json
  label: Audo API API
  slug: audo-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audo-ai/openapi/_original/audo-ai-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account is for one person.
    type: individual
  minimum_age:
    text: You must be at least 13, and old enough to agree to these terms where you live.
    value: '13'
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
name: Audo
provenance_date: '2026-11-09'
provider_name: Audo
provider_slug: audo-ai
slug: audo-ai-eligibility
source_date: '2026-11-09'
source_filename: audo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://audo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Audo\naid: audo-ai\nurl: https://audo.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account is for one person.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13, and old enough to agree to these terms where you live.\n"
source_yaml_url: https://artifacts.apis.io/audo-ai/eligibility/audo-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Audo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Audio
- Video
- Tools
---
