---
api_specs:
- filename: mem0-agents-api-openapi.yml
  format: yaml
  label: Mem0 Agents API
  slug: mem0-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-agents-api-openapi.yml
- filename: mem0-apps-api-openapi.yml
  format: yaml
  label: Mem0 Apps API
  slug: mem0-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-apps-api-openapi.yml
- filename: mem0-entities-api-openapi.yml
  format: yaml
  label: Mem0 Entities API
  slug: mem0-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-entities-api-openapi.yml
- filename: mem0-events-api-openapi.yml
  format: yaml
  label: Mem0 Events API
  slug: mem0-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-events-api-openapi.yml
- filename: mem0-exports-api-openapi.yml
  format: yaml
  label: Mem0 Exports API
  slug: mem0-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-exports-api-openapi.yml
- filename: mem0-feedback-api-openapi.yml
  format: yaml
  label: Mem0 Feedback API
  slug: mem0-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-feedback-api-openapi.yml
- filename: mem0-memories-api-openapi.yml
  format: yaml
  label: Mem0 Memories API
  slug: mem0-memories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-memories-api-openapi.yml
- filename: mem0-organizations-api-openapi.yml
  format: yaml
  label: Mem0 Organizations API
  slug: mem0-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-organizations-api-openapi.yml
- filename: mem0-project-api-openapi.yml
  format: yaml
  label: Mem0 Project API
  slug: mem0-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-project-api-openapi.yml
- filename: mem0-projects-api-openapi.yml
  format: yaml
  label: Mem0 Projects API
  slug: mem0-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-projects-api-openapi.yml
- filename: mem0-runs-api-openapi.yml
  format: yaml
  label: Mem0 Runs API
  slug: mem0-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-runs-api-openapi.yml
- filename: mem0-stats-api-openapi.yml
  format: yaml
  label: Mem0 Stats API
  slug: mem0-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-stats-api-openapi.yml
- filename: mem0-users-api-openapi.yml
  format: yaml
  label: Mem0 Users API
  slug: mem0-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-users-api-openapi.yml
- filename: mem0-webhooks-api-openapi.yml
  format: yaml
  label: Mem0 Webhooks API
  slug: mem0-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-webhooks-api-openapi.yml
- filename: mem0-dream-api-openapi.yml
  format: yaml
  label: Mem0 Dream API
  slug: mem0-dream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-dream-api-openapi.yml
- filename: mem0-profiles-api-openapi.yml
  format: yaml
  label: Mem0 Profiles API
  slug: mem0-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mem0/openapi/mem0-profiles-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not located in a country subject to a U.S. Government embargo or designated as a 'terrorist supporting' country, and is not listed on U.S. Government lists of prohibited or restricted parties.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Prohibited Data uploads
    text: Customer shall not upload or transmit any Prohibited Data to the Mem0 Service except as expressly authorized in writing by Mem0.
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
name: Mem0
provenance_date: '2026-11-10'
provider_name: Mem0
provider_slug: mem0
slug: mem0-eligibility
source_date: '2026-11-10'
source_filename: mem0-eligibility.yml
source_heading: Eligibility
source_page: https://mem0.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mem0\naid: mem0\nurl: https://mem0.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not located in a country subject to a U.S. Government embargo or designated as\n    a 'terrorist supporting' country, and is not listed on U.S. Government lists of prohibited or restricted parties.\nentity_types: []\nrestricted_uses:\n- summary: No Prohibited Data uploads\n  text: Customer shall not upload or transmit any Prohibited Data to the Mem0 Service except as expressly authorized\n    in writing by Mem0.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mem0/eligibility/mem0-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Mem0's own page on 2026-11-10.
synthetic: false
tags:
- Memory
- AI Agents
- Agent Memory
- Context
- LLM
- Retrieval
- Vectors
- LangChain
- CrewAI
- AutoGen
- LlamaIndex
- Open Source
- Infrastructure
---
