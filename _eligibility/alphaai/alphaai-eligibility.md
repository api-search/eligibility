---
api_specs:
- filename: alphaai-calendar-api-openapi.yml
  format: yaml
  label: AlphaAI Calendar API
  slug: alphaai-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-calendar-api-openapi.yml
- filename: alphaai-news-api-openapi.yml
  format: yaml
  label: AlphaAI News API
  slug: alphaai-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-news-api-openapi.yml
- filename: alphaai-symbols-api-openapi.yml
  format: yaml
  label: AlphaAI Symbols API
  slug: alphaai-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-symbols-api-openapi.yml
- filename: alphaai-coverage-api-openapi.yml
  format: yaml
  label: AlphaAI Coverage API
  slug: alphaai-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-coverage-api-openapi.yml
- filename: alphaai-radar-api-openapi.yml
  format: yaml
  label: AlphaAI Radar API
  slug: alphaai-radar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-radar-api-openapi.yml
- filename: alphaai-stories-api-openapi.yml
  format: yaml
  label: AlphaAI Stories API
  slug: alphaai-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-stories-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old or the age of majority in your jurisdiction
    type: individual
  - text: One account per person (or one per organization for business use).
    type: business
  minimum_age:
    text: You are at least 18 years old or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Illegal activity or market manipulation
    text: Use the Service for illegal activities or market manipulation
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
name: AlphaAI
provenance_date: '2026-11-09'
provider_name: AlphaAI
provider_slug: alphaai
slug: alphaai-eligibility
source_date: '2026-11-09'
source_filename: alphaai-eligibility.yml
source_heading: Eligibility
source_page: https://alphai.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlphaAI\naid: alphaai\nurl: https://alphai.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old or the age of majority in your jurisdiction\n- type: business\n  text: One account per person (or one per organization for business use).\nrestricted_uses:\n- summary: Illegal activity or market manipulation\n  text: Use the Service for illegal activities or market manipulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are\
  \ at least 18 years old or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/alphaai/eligibility/alphaai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AlphaAI's own page on 2026-11-09.
synthetic: false
tags:
- Financial News
- Stock Market
- SEC Filings
- Insider Trading
- Fintech
- Market Data
- Sentiment
- AI Agents
- MCP
- LLM
- Trading
---
