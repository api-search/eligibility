---
api_specs:
- filename: neuralverge-api-ai-agents-api-openapi.yml
  format: yaml
  label: NeuralVerge API AI Agents API
  slug: neuralverge-api-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neuralverge-api/openapi/neuralverge-api-ai-agents-api-openapi.yml
- filename: neuralverge-api-ai-extract-api-openapi.yml
  format: yaml
  label: NeuralVerge API AI Extract API
  slug: neuralverge-api-ai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neuralverge-api/openapi/neuralverge-api-ai-extract-api-openapi.yml
- filename: neuralverge-api-ai-research-api-openapi.yml
  format: yaml
  label: NeuralVerge API AI Research API
  slug: neuralverge-api-ai-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neuralverge-api/openapi/neuralverge-api-ai-research-api-openapi.yml
- filename: neuralverge-api-data-sources-api-openapi.yml
  format: yaml
  label: NeuralVerge API Data Sources API
  slug: neuralverge-api-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neuralverge-api/openapi/neuralverge-api-data-sources-api-openapi.yml
- filename: neuralverge-api-search-api-openapi.yml
  format: yaml
  label: NeuralVerge API Search API
  slug: neuralverge-api-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neuralverge-api/openapi/neuralverge-api-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for business and professional use by individuals at least 18 years old (or the age of majority in their jurisdiction) able to form a binding contract.
    type: individual
  minimum_age:
    text: at least 18 years old (or the age of majority in their jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Not sole basis for decisions about individuals
    text: You must not use them as the sole basis for any decision about an individual’s credit, employment, insurance, housing, or eligibility for a benefit.
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
name: NeuralVerge API
provenance_date: '2026-11-10'
provider_name: NeuralVerge API
provider_slug: neuralverge-api
slug: neuralverge-api-eligibility
source_date: '2026-11-10'
source_filename: neuralverge-api-eligibility.yml
source_heading: Eligibility
source_page: https://neuralverge.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NeuralVerge API\naid: neuralverge-api\nurl: https://neuralverge.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for business and professional use by individuals at least 18 years old (or the age\n    of majority in their jurisdiction) able to form a binding contract.\nrestricted_uses:\n- summary: Not sole basis for decisions about individuals\n  text: You must not use them as the sole basis for any decision about an individual’s credit, employment, insurance,\n    housing, or eligibility for a benefit.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years old (or the age of majority in their jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/neuralverge-api/eligibility/neuralverge-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from NeuralVerge API's own page on 2026-11-10.
synthetic: false
tags:
- Company Data
- People Data
- Contact Enrichment
- Email Finder
- Email Verification
- Phone Lookup
- corporate registries
- KYB / compliance
- Web Extraction
- Deep Research
- Web Search
- LinkedIn data
- MCP
- AI Agents
- A2A
- Data Enrichment
---
