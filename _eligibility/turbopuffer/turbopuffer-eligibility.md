---
api_specs:
- filename: turbopuffer-namespaces-api-openapi.yml
  format: yaml
  label: turbopuffer Namespaces API
  slug: turbopuffer-namespaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/turbopuffer/openapi/turbopuffer-namespaces-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: or an individual who is at least 18 years old
    type: individual
  minimum_age:
    text: an individual who is at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited Data and high-risk activities
    text: Customer must not use the Service with Prohibited Data or for High Risk Activities.
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
name: turbopuffer
provenance_date: '2026-11-10'
provider_name: turbopuffer
provider_slug: turbopuffer
slug: turbopuffer-eligibility
source_date: '2026-11-10'
source_filename: turbopuffer-eligibility.yml
source_heading: Eligibility
source_page: https://turbopuffer.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: turbopuffer\naid: turbopuffer\nurl: https://turbopuffer.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: or an individual who is at least 18 years old\nrestricted_uses:\n- summary: Prohibited Data and high-risk activities\n  text: Customer must not use the Service with Prohibited Data or for High Risk Activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: an individual who is at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/turbopuffer/eligibility/turbopuffer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from turbopuffer's own page on 2026-11-10.
synthetic: false
tags:
- Vector Search
- Full-Text Search
- Hybrid Search
- BM25
- Serverless
- Object Storage
- RAG
- Semantic Search
- AI Infrastructure
- Embeddings
---
