---
api_specs:
- filename: karumi-analytics-api-openapi.yml
  format: yaml
  label: Karumi Analytics API
  slug: karumi-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karumi/openapi/karumi-analytics-api-openapi.yml
- filename: karumi-sessions-api-openapi.yml
  format: yaml
  label: Karumi Sessions API
  slug: karumi-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karumi/openapi/karumi-sessions-api-openapi.yml
- filename: karumi-targets-api-openapi.yml
  format: yaml
  label: Karumi Targets API
  slug: karumi-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karumi/openapi/karumi-targets-api-openapi.yml
- filename: karumi-chat-onboarding-api-openapi.yml
  format: yaml
  label: Karumi Chat onboarding API
  slug: karumi-chat-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karumi/openapi/karumi-chat-onboarding-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The AI Demo Services are intended for use by individuals who are 16 years of age or older.
    type: individual
  - text: If you are agreeing to this Agreement on behalf of a company, business, or other legal entity, you represent and warrant that you have the authority to bind such entity to this Agreement
    type: business
  minimum_age:
    text: The AI Demo Services are intended for use by individuals who are 16 years of age or older. If you are under 16 years old, you must obtain the consent of a parent or legal guardian before using the AI Demo Services.
    value: '16'
  restricted_uses:
  - summary: Third-party rights and participant notice
    text: You are responsible for ensuring that all participants in video calls are properly informed that an AI agent is conducting the demonstration.
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
name: Karumi
provenance_date: '2026-11-09'
provider_name: Karumi
provider_slug: karumi
slug: karumi-eligibility
source_date: '2026-11-09'
source_filename: karumi-eligibility.yml
source_heading: Eligibility
source_page: https://karumi.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Karumi\naid: karumi\nurl: https://karumi.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The AI Demo Services are intended for use by individuals who are 16 years of age or older.\n- type: business\n  text: If you are agreeing to this Agreement on behalf of a company, business, or other legal entity, you represent\n    and warrant that you have the authority to bind such entity to this Agreement\nrestricted_uses:\n- summary: Third-party rights and participant notice\n  text: You are responsible for ensuring that all participants\
  \ in video calls are properly informed that an AI agent\n    is conducting the demonstration.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The AI Demo Services are intended for use by individuals who are 16 years of age or older. If you are under\n    16 years old, you must obtain the consent of a parent or legal guardian before using the AI Demo Services.\n"
source_yaml_url: https://artifacts.apis.io/karumi/eligibility/karumi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Karumi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Product Demos
- Sales Enablement
- Go-To-Market
- Software-as-a-Service
- Conversational AI
- Video
- Y Combinator
- MCP
- Agent-Native
- Analytics
- Conversation Intelligence
---
