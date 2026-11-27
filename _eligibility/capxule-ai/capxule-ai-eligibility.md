---
api_specs:
- filename: capxule-ai-account-api-openapi.yml
  format: yaml
  label: Capxule Account API
  slug: capxule-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capxule-ai/openapi/capxule-ai-account-api-openapi.yml
- filename: capxule-ai-catalog-api-openapi.yml
  format: yaml
  label: Capxule Catalog API
  slug: capxule-ai-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capxule-ai/openapi/capxule-ai-catalog-api-openapi.yml
- filename: capxule-ai-plan-api-openapi.yml
  format: yaml
  label: Capxule Plan API
  slug: capxule-ai-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capxule-ai/openapi/capxule-ai-plan-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 in the European Union or 13 in the United States.
    value: 16 (EU) / 13 (US)
  restricted_uses:
  - summary: no password requests
    text: ask for, accept or relay a password
  - summary: no payment or plan promotion
    text: say a price, a plan name as a pitch, or a checkout link to the human
  - source: https://capxule.com/terms
    summary: Harmful, illegal or misleading content
    text: You may not use the Service to distribute harmful, illegal, or misleading content.
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
name: Capxule
provenance_date: '2026-11-09'
provider_name: Capxule
provider_slug: capxule-ai
slug: capxule-ai-eligibility
source_date: '2026-11-09'
source_filename: capxule-ai-eligibility.yml
source_heading: Eligibility
source_page: https://capxule.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capxule\naid: capxule-ai\nurl: https://capxule.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://capxule.ai/terms\n  - https://capxule.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: no password requests\n  text: ask for, accept or relay a password\n- summary: no payment or plan promotion\n  text: say a price, a plan name as a pitch, or a checkout link to the human\n- summary: Harmful, illegal or misleading content\n  text: You may not use the Service to distribute harmful, illegal, or misleading content.\n  source: https://capxule.com/terms\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 16 (EU) / 13 (US)\n  text: You must be at least 16 in the European Union or 13 in the United States.\n"
source_yaml_url: https://artifacts.apis.io/capxule-ai/eligibility/capxule-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Capxule's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Context Marketplace
- Artificial Intelligence
- AI Agents
- MCP
- Education
- Test Preparation
- Knowledge
---
