---
api_specs:
- filename: vectara-agents-api-openapi.yml
  format: yaml
  label: Vectara Agents API
  slug: vectara-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectara/openapi/vectara-agents-api-openapi.yml
- filename: vectara-authentication-api-openapi.yml
  format: yaml
  label: Vectara Authentication API
  slug: vectara-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectara/openapi/vectara-authentication-api-openapi.yml
- filename: vectara-corpora-api-openapi.yml
  format: yaml
  label: Vectara Corpora API
  slug: vectara-corpora-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectara/openapi/vectara-corpora-api-openapi.yml
- filename: vectara-documents-api-openapi.yml
  format: yaml
  label: Vectara Documents API
  slug: vectara-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectara/openapi/vectara-documents-api-openapi.yml
- filename: vectara-pipelines-api-openapi.yml
  format: yaml
  label: Vectara Pipelines API
  slug: vectara-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectara/openapi/vectara-pipelines-api-openapi.yml
- filename: vectara-query-api-openapi.yml
  format: yaml
  label: Vectara Query API
  slug: vectara-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectara/openapi/vectara-query-api-openapi.yml
- filename: vectara-tools-api-openapi.yml
  format: yaml
  label: Vectara Tools API
  slug: vectara-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectara/openapi/vectara-tools-api-openapi.yml
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
  - summary: Export control restrictions
    text: not to export or re-export any of the Content to countries or persons prohibited under the export control laws
  - summary: U.S. Government restricted rights
    text: The Content is provided with “RESTRICTED RIGHTS.”
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
name: Vectara
provenance_date: '2026-11-10'
provider_name: Vectara
provider_slug: vectara
slug: vectara-eligibility
source_date: '2026-11-10'
source_filename: vectara-eligibility.yml
source_heading: Eligibility
source_page: https://www.vectara.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vectara\naid: vectara\nurl: https://www.vectara.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control restrictions\n  text: not to export or re-export any of the Content to countries or persons prohibited under the export control\n    laws\n- summary: U.S. Government restricted rights\n  text: The Content is provided with “RESTRICTED RIGHTS.”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vectara/eligibility/vectara-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Vectara's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Corpora
- Embeddings
- Enterprise Search
- Generative AI
- Grounded Generation
- Hallucination Detection
- LLM
- MCP
- RAG
- Retrieval
- Search
- Semantic Search
- Vector Search
---
