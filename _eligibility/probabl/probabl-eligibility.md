---
api_specs:
- filename: probabl-anthropic-compatible-agent-api-openapi.yml
  format: yaml
  label: Probabl Anthropic Compatible Agent API
  slug: probabl-anthropic-compatible-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-anthropic-compatible-agent-api-openapi.yml
- filename: probabl-health-api-openapi.yml
  format: yaml
  label: Probabl Health API
  slug: probabl-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-health-api-openapi.yml
- filename: probabl-identity-api-openapi.yml
  format: yaml
  label: Probabl Identity API
  slug: probabl-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-identity-api-openapi.yml
- filename: probabl-liveness-api-openapi.yml
  format: yaml
  label: Probabl Liveness API
  slug: probabl-liveness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-liveness-api-openapi.yml
- filename: probabl-llm-provider-api-openapi.yml
  format: yaml
  label: Probabl LLM Provider API
  slug: probabl-llm-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-llm-provider-api-openapi.yml
- filename: probabl-openai-compatible-agent-api-openapi.yml
  format: yaml
  label: Probabl OpenAI Compatible Agent API
  slug: probabl-openai-compatible-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-openai-compatible-agent-api-openapi.yml
- filename: probabl-projects-api-openapi.yml
  format: yaml
  label: Probabl Projects API
  slug: probabl-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-projects-api-openapi.yml
- filename: probabl-readiness-api-openapi.yml
  format: yaml
  label: Probabl Readiness API
  slug: probabl-readiness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-readiness-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any person who subscribes to, accesses, or uses the Service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, harmful or offensive use
    text: Use the Service for any illegal, harmful, or offensive purposes.
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
name: Probabl
provenance_date: '2026-11-10'
provider_name: Probabl
provider_slug: probabl
slug: probabl-eligibility
source_date: '2026-11-10'
source_filename: probabl-eligibility.yml
source_heading: Eligibility
source_page: https://www.probabl.ai/legal/skore-eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Probabl\naid: probabl\nurl: https://www.probabl.ai/legal/skore-eula/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any person who subscribes to, accesses, or uses the Service.\nrestricted_uses:\n- summary: Illegal, harmful or offensive use\n  text: Use the Service for any illegal, harmful, or offensive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/probabl/eligibility/probabl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Probabl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Source
- Machine Learning
- Data Science
- scikit-learn
- MLOps
- Model Evaluation
- Experiment Tracking
- Agent Skills
- Artificial Intelligence
- Python
- France
---
