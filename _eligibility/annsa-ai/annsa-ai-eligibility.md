---
api_specs:
- filename: annsa-ai-agents-api-openapi.yml
  format: yaml
  label: Annsa Agents API
  slug: annsa-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/annsa-ai/openapi/annsa-ai-agents-api-openapi.yml
- filename: annsa-ai-ingest-api-openapi.yml
  format: yaml
  label: Annsa Ingest API
  slug: annsa-ai-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/annsa-ai/openapi/annsa-ai-ingest-api-openapi.yml
- filename: annsa-ai-service-api-openapi.yml
  format: yaml
  label: Annsa Service API
  slug: annsa-ai-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/annsa-ai/openapi/annsa-ai-service-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Annsa is a B2B service for professionals
    type: business
  minimum_age:
    text: You must be at least 18 years old (Annsa is a B2B service for professionals)
    value: '18'
  restricted_uses:
  - summary: Illegal purposes, malware, unauthorized access, resale
    text: 'You may not: Use the service for illegal purposes'
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
name: Annsa
provenance_date: '2026-11-09'
provider_name: Annsa
provider_slug: annsa-ai
slug: annsa-ai-eligibility
source_date: '2026-11-09'
source_filename: annsa-ai-eligibility.yml
source_heading: Eligibility
source_page: https://annsa.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Annsa\naid: annsa-ai\nurl: https://annsa.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Annsa is a B2B service for professionals\nrestricted_uses:\n- summary: Illegal purposes, malware, unauthorized access, resale\n  text: 'You may not: Use the service for illegal purposes'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (Annsa is a B2B service for professionals)\n"
source_yaml_url: https://artifacts.apis.io/annsa-ai/eligibility/annsa-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Annsa's own page on 2026-11-09.
synthetic: false
tags:
- Project Management
- Customer Management
- Agent Teams
- Artificial Intelligence
- Software-as-a-Service
---
