---
api_specs:
- filename: empiriolabs-ai-chatcompletions-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Chat Completions API
  slug: empiriolabs-ai-chatcompletions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-chatcompletions-api-openapi.yml
- filename: empiriolabs-ai-completions-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Completions API
  slug: empiriolabs-ai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-completions-api-openapi.yml
- filename: empiriolabs-ai-gemini-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Gemini API
  slug: empiriolabs-ai-gemini-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-gemini-api-openapi.yml
- filename: empiriolabs-ai-messages-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Messages API
  slug: empiriolabs-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-messages-api-openapi.yml
- filename: empiriolabs-ai-models-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Models API
  slug: empiriolabs-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-models-api-openapi.yml
- filename: empiriolabs-ai-responses-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Responses API
  slug: empiriolabs-ai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-responses-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Plans are for your own personal use.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the services.
    value: '18'
  restricted_uses:
  - summary: High-impact decisions
    text: high-impact decisions without appropriate professional review and legal authority
  - summary: Non-consensual or minor sexual content
    text: non-consensual sexual content, sexual content involving minors, impersonation, deceptive voice or likeness use
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
name: EmpirioLabs AI
provenance_date: '2026-11-09'
provider_name: EmpirioLabs AI
provider_slug: empiriolabs-ai
slug: empiriolabs-ai-eligibility
source_date: '2026-11-09'
source_filename: empiriolabs-ai-eligibility.yml
source_heading: Eligibility
source_page: https://empiriolabs.ai/policy/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EmpirioLabs AI\naid: empiriolabs-ai\nurl: https://empiriolabs.ai/policy/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Plans are for your own personal use.\nrestricted_uses:\n- summary: High-impact decisions\n  text: high-impact decisions without appropriate professional review and legal authority\n- summary: Non-consensual or minor sexual content\n  text: non-consensual sexual content, sexual content involving minors, impersonation, deceptive voice or likeness\n    use\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the services.\n"
source_yaml_url: https://artifacts.apis.io/empiriolabs-ai/eligibility/empiriolabs-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EmpirioLabs AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Inference
- Cloud
- Platform
---
