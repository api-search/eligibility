---
api_specs:
- filename: perplexity-asyncapi.yml
  format: yaml
  label: Perplexity Async Chat Completions API
  slug: async-chat-completions-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/perplexity/asyncapi/perplexity-asyncapi.yml
- filename: perplexity-asyncapi.yml
  format: yaml
  label: Perplexity Responses API
  slug: responses-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/perplexity/asyncapi/perplexity-asyncapi.yml
- filename: perplexity-agent-api-openapi.yml
  format: yaml
  label: Perplexity Agent API
  slug: perplexity-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-agent-api-openapi.yml
- filename: perplexity-async-api-openapi.yml
  format: yaml
  label: Perplexity Async API
  slug: perplexity-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-async-api-openapi.yml
- filename: perplexity-contextualizedembeddings-api-openapi.yml
  format: yaml
  label: Perplexity Contextualizedembeddings API
  slug: perplexity-contextualizedembeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-contextualizedembeddings-api-openapi.yml
- filename: perplexity-embeddings-api-openapi.yml
  format: yaml
  label: Perplexity Embeddings API
  slug: perplexity-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-embeddings-api-openapi.yml
- filename: perplexity-models-api-openapi.yml
  format: yaml
  label: Perplexity Models API
  slug: perplexity-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-models-api-openapi.yml
- filename: perplexity-search-api-openapi.yml
  format: yaml
  label: Perplexity Search API
  slug: perplexity-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-search-api-openapi.yml
- filename: perplexity-decisions-api-openapi.yml
  format: yaml
  label: Perplexity Decisions API
  slug: perplexity-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-decisions-api-openapi.yml
- filename: perplexity-sonar-api-openapi.yml
  format: yaml
  label: Perplexity Sonar API
  slug: perplexity-sonar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-sonar-api-openapi.yml
- filename: perplexity-admin-api-openapi.yml
  format: yaml
  label: Perplexity Admin API
  slug: perplexity-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-admin-api-openapi.yml
- filename: perplexity-analytics-api-openapi.yml
  format: yaml
  label: Perplexity Analytics API
  slug: perplexity-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-analytics-api-openapi.yml
- filename: perplexity-batches-api-openapi.yml
  format: yaml
  label: Perplexity Batches API
  slug: perplexity-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-batches-api-openapi.yml
- filename: perplexity-skills-api-openapi.yml
  format: yaml
  label: Perplexity Skills API
  slug: perplexity-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perplexity/openapi/perplexity-skills-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity
    type: business
  - source: https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service
    text: the organization on whose behalf you are accessing or using the Services (“Customer”)
    type: business
  minimum_age:
    text: You must be 13 years of age or older to use the Services.
    value: '13'
  restricted_uses:
  - summary: Export restrictions
    text: You agree that you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by the Company hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
  - source: https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service
    summary: Protected health information
    text: Customer may not use the Services to create, receive, maintain, transmit, or otherwise process any information that includes or constitutes “Protected Health Information”
  verification:
    approval_required: null
    kyb: null
    kyc: null
    source: https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service
    text: Customer shall cooperate with requests for information from Perplexity to support compliance with its AUP, including to verify Customer’s identity and use of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Perplexity
provenance_date: '2026-11-10'
provider_name: Perplexity
provider_slug: perplexity
slug: perplexity-eligibility
source_date: '2026-11-10'
source_filename: perplexity-eligibility.yml
source_heading: Eligibility
source_page: https://www.perplexity.ai/hub/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Perplexity\naid: perplexity\nurl: https://www.perplexity.ai/hub/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service\n  - https://www.perplexity.ai/hub/legal/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity\n- type: business\n  text: the organization on whose behalf you are accessing or using the Services (“Customer”)\n  source: https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service\n\
  restricted_uses:\n- summary: Export restrictions\n  text: You agree that you will not export or re-export, directly or indirectly, the Services and/or other information\n    or materials provided by the Company hereunder, to any country for which the United States or any other relevant\n    jurisdiction requires any export license\n- summary: Protected health information\n  text: Customer may not use the Services to create, receive, maintain, transmit, or otherwise process any information\n    that includes or constitutes “Protected Health Information”\n  source: https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer shall cooperate with requests for information from Perplexity to support compliance with its AUP,\n    including to verify Customer’s identity and use of the Services.\n  source: https://www.perplexity.ai/hub/legal/perplexity-api-terms-of-service\nminimum_age:\n  value: '13'\n\
  \  text: You must be 13 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/perplexity/eligibility/perplexity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Perplexity's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Search
- Agents
- Embeddings
- Research
- Agentic Commerce
- Foundation Models
---
