---
api_specs:
- filename: parallel-ai-chat-api-beta-api-openapi.yml
  format: yaml
  label: Parallel Chat API (Beta) API
  slug: parallel-ai-chat-api-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-chat-api-beta-api-openapi.yml
- filename: parallel-ai-extract-api-openapi.yml
  format: yaml
  label: Parallel Extract API
  slug: parallel-ai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-extract-api-openapi.yml
- filename: parallel-ai-findall-api-openapi.yml
  format: yaml
  label: Parallel Find All API
  slug: parallel-ai-findall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-findall-api-openapi.yml
- filename: parallel-ai-memory-api-openapi.yml
  format: yaml
  label: Parallel Memory API
  slug: parallel-ai-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-memory-api-openapi.yml
- filename: parallel-ai-monitor-api-openapi.yml
  format: yaml
  label: Parallel Monitor API
  slug: parallel-ai-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-monitor-api-openapi.yml
- filename: parallel-ai-responses-api-api-openapi.yml
  format: yaml
  label: Parallel Responses API
  slug: parallel-ai-responses-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-responses-api-api-openapi.yml
- filename: parallel-ai-search-api-openapi.yml
  format: yaml
  label: Parallel Search API
  slug: parallel-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-search-api-openapi.yml
- filename: parallel-ai-decisions-api-openapi.yml
  format: yaml
  label: Parallel Decisions API
  slug: parallel-ai-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-decisions-api-openapi.yml
- filename: parallel-ai-apps-api-openapi.yml
  format: yaml
  label: Parallel Apps API
  slug: parallel-ai-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-apps-api-openapi.yml
- filename: parallel-ai-balance-api-openapi.yml
  format: yaml
  label: Parallel Balance API
  slug: parallel-ai-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-balance-api-openapi.yml
- filename: parallel-ai-image-search-api-openapi.yml
  format: yaml
  label: Parallel Image Search API
  slug: parallel-ai-image-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-image-search-api-openapi.yml
- filename: parallel-ai-keys-api-openapi.yml
  format: yaml
  label: Parallel Keys API
  slug: parallel-ai-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-keys-api-openapi.yml
- filename: parallel-ai-place-search-api-openapi.yml
  format: yaml
  label: Parallel Place Search API
  slug: parallel-ai-place-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-place-search-api-openapi.yml
- filename: parallel-ai-usage-api-openapi.yml
  format: yaml
  label: Parallel Usage API
  slug: parallel-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-usage-api-openapi.yml
- filename: parallel-ai-tasks-api-openapi.yml
  format: yaml
  label: Parallel Tasks API
  slug: parallel-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-tasks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: if you are a child under 16 years of age, please do not attempt to register for or otherwise use our websites or send us any personal information.
    value: '16'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You will only use our websites in a manner that complies with all laws that apply to you.
  - summary: Harmful or fraudulent use
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
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
name: Parallel
provenance_date: '2026-11-10'
provider_name: Parallel
provider_slug: parallel-ai
slug: parallel-ai-eligibility
source_date: '2026-11-10'
source_filename: parallel-ai-eligibility.yml
source_heading: Eligibility
source_page: https://parallel.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parallel\naid: parallel-ai\nurl: https://parallel.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You will only use our websites in a manner that complies with all laws that apply to you.\n- summary: Harmful or fraudulent use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: if you are a child under 16 years of age, please do not attempt to register for or otherwise use our websites\n    or send us any personal information.\n"
source_yaml_url: https://artifacts.apis.io/parallel-ai/eligibility/parallel-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Parallel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Web Search
- Agents
- Deep Research
- Web Extraction
- Data Enrichment
- Web Monitoring
- LLM Tools
- A2A
- AI Agents
- MCP
- Agent Skills
- Content Extraction
- Entity Resolution
---
