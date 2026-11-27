---
api_specs:
- filename: kitforai-batch-api-openapi.yml
  format: yaml
  label: Kit For AI Batch API
  slug: kitforai-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kitforai/openapi/kitforai-batch-api-openapi.yml
- filename: kitforai-convert-api-openapi.yml
  format: yaml
  label: Kit For AI Convert API
  slug: kitforai-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kitforai/openapi/kitforai-convert-api-openapi.yml
- filename: kitforai-knowledge-bases-api-openapi.yml
  format: yaml
  label: Kit For AI Knowledge Bases API
  slug: kitforai-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kitforai/openapi/kitforai-knowledge-bases-api-openapi.yml
claim_count: 1
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
  - summary: Unlawful purposes
    text: Do not use the service for unlawful purposes.
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
name: Kit For AI
provenance_date: '2026-11-09'
provider_name: Kit For AI
provider_slug: kitforai
slug: kitforai-eligibility
source_date: '2026-11-09'
source_filename: kitforai-eligibility.yml
source_heading: Eligibility
source_page: https://kitforai.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kit For AI\naid: kitforai\nurl: https://kitforai.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Do not use the service for unlawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kitforai/eligibility/kitforai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Kit For AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Document Conversion
- RAG
- Knowledge Base
---
