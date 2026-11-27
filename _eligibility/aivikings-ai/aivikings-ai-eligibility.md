---
api_specs:
- filename: aivikings-ai-prices-api-openapi.yml
  format: yaml
  label: AiVikings.ai Prices API
  slug: aivikings-ai-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivikings-ai/openapi/aivikings-ai-prices-api-openapi.yml
- filename: aivikings-ai-pricing-api-openapi.yml
  format: yaml
  label: AiVikings.ai Pricing API
  slug: aivikings-ai-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivikings-ai/openapi/aivikings-ai-pricing-api-openapi.yml
- filename: aivikings-ai-quote-api-openapi.yml
  format: yaml
  label: AiVikings.ai Quote API
  slug: aivikings-ai-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivikings-ai/openapi/aivikings-ai-quote-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  - text: You may use the services as a business or as a consumer.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
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
name: AiVikings.ai
provenance_date: '2026-11-09'
provider_name: AiVikings.ai
provider_slug: aivikings-ai
slug: aivikings-ai-eligibility
source_date: '2026-11-09'
source_filename: aivikings-ai-eligibility.yml
source_heading: Eligibility
source_page: https://aivikings.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AiVikings.ai\naid: aivikings-ai\nurl: https://aivikings.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\n- type: business\n  text: You may use the services as a business or as a consumer.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/aivikings-ai/eligibility/aivikings-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from AiVikings.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Domain Registrar
- MCP
- REST API
- DNS
- Automation
---
