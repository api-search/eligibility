---
api_specs:
- filename: schemasure-health-api-openapi.yml
  format: yaml
  label: SchemaSure Health API
  slug: schemasure-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-health-api-openapi.yml
- filename: schemasure-image-extraction-x402-v2-api-openapi.yml
  format: yaml
  label: SchemaSure Image extraction · x402 V2 API
  slug: schemasure-image-extraction-x402-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-image-extraction-x402-v2-api-openapi.yml
- filename: schemasure-legacy-v1-evaluation-api-api-openapi.yml
  format: yaml
  label: SchemaSure Legacy V1 evaluation API
  slug: schemasure-legacy-v1-evaluation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-legacy-v1-evaluation-api-api-openapi.yml
- filename: schemasure-primary-x402-v2-api-api-openapi.yml
  format: yaml
  label: SchemaSure Primary x402 V2 API
  slug: schemasure-primary-x402-v2-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-primary-x402-v2-api-api-openapi.yml
- filename: schemasure-business-time-api-openapi.yml
  format: yaml
  label: SchemaSure Business Time API
  slug: schemasure-business-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-business-time-api-openapi.yml
- filename: schemasure-chain-api-openapi.yml
  format: yaml
  label: SchemaSure Chain API
  slug: schemasure-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-chain-api-openapi.yml
- filename: schemasure-guard-api-openapi.yml
  format: yaml
  label: SchemaSure Guard API
  slug: schemasure-guard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-guard-api-openapi.yml
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
  - summary: Unlawful or disruptive use
    text: You may not use the Service to violate any law or to attempt to disrupt, overload, or reverse-engineer its infrastructure.
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
name: SchemaSure
provenance_date: '2026-11-10'
provider_name: SchemaSure
provider_slug: schemasure
slug: schemasure-eligibility
source_date: '2026-11-10'
source_filename: schemasure-eligibility.yml
source_heading: Eligibility
source_page: https://schemasure.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SchemaSure\naid: schemasure\nurl: https://schemasure.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or disruptive use\n  text: You may not use the Service to violate any law or to attempt to disrupt, overload, or reverse-engineer its\n    infrastructure.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/schemasure/eligibility/schemasure-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from SchemaSure's own page on 2026-11-10.
synthetic: false
tags:
- Structured Data Extraction
- text-to-JSON
- JSON Schema
- Document Parsing
- Data Cleaning
- LLM Tooling
- AI Agents
- x402-micropayments
- Agent-Native
- A2A
- MCP
---
