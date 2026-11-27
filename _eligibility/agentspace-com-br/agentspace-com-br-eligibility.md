---
api_specs:
- filename: agentspace-com-br-account-api-openapi.yml
  format: yaml
  label: AgentSpace Account API
  slug: agentspace-com-br-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-account-api-openapi.yml
- filename: agentspace-com-br-agent-api-openapi.yml
  format: yaml
  label: AgentSpace Agent API
  slug: agentspace-com-br-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-agent-api-openapi.yml
- filename: agentspace-com-br-billing-api-openapi.yml
  format: yaml
  label: AgentSpace Billing API
  slug: agentspace-com-br-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-billing-api-openapi.yml
- filename: agentspace-com-br-review-api-openapi.yml
  format: yaml
  label: AgentSpace Review API
  slug: agentspace-com-br-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-review-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Você precisa ter 18 anos ou mais.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: 'É proibido usar o AgentSpace para: phishing'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As informações de cadastro precisam ser verdadeiras.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentSpace
provenance_date: '2026-11-09'
provider_name: AgentSpace
provider_slug: agentspace-com-br
slug: agentspace-com-br-eligibility
source_date: '2026-11-09'
source_filename: agentspace-com-br-eligibility.yml
source_heading: Eligibility
source_page: https://agentspace.com.br/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentSpace\naid: agentspace-com-br\nurl: https://agentspace.com.br/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses\n  text: 'É proibido usar o AgentSpace para: phishing'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As informações de cadastro precisam ser verdadeiras.\nminimum_age:\n  value: '18'\n  text: Você precisa ter 18 anos ou mais.\n"
source_yaml_url: https://artifacts.apis.io/agentspace-com-br/eligibility/agentspace-com-br-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from AgentSpace's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Workspace
- Sandbox
- Hosting
---
