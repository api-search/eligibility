---
api_specs:
- filename: converra-ai-api-openapi-generated.yml
  format: yaml
  label: Converra API Reference API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-api-openapi-generated.yml
- filename: converra-ai-core-openapi-generated.yml
  format: yaml
  label: Converra core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-core-openapi-generated.yml
- filename: converra-ai-guide-openapi-generated.yml
  format: yaml
  label: Converra Guide API
  slug: guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-guide-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself or your organization.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself or your organization.
    value: '18'
  restricted_uses:
  - summary: High-risk environments
    text: The Service is not designed for use in high-risk environments where failure could lead directly to death, personal injury, or severe physical or environmental damage
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
name: Converra
provenance_date: '2026-11-09'
provider_name: Converra
provider_slug: converra-ai
slug: converra-ai-eligibility
source_date: '2026-11-09'
source_filename: converra-ai-eligibility.yml
source_heading: Eligibility
source_page: https://converra.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Converra\naid: converra-ai\nurl: https://converra.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself\n    or your organization.\nrestricted_uses:\n- summary: High-risk environments\n  text: The Service is not designed for use in high-risk environments where failure could lead directly to death,\n    personal injury, or severe physical or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself\n    or your organization.\n"
source_yaml_url: https://artifacts.apis.io/converra-ai/eligibility/converra-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Converra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Optimization
- LLM Observability
- Simulation Testing
- Prompt Engineering
- MCP
---
