---
api_specs:
- filename: atako-ai-api-openapi.json
  format: json
  label: Atako API API
  slug: atako-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atako-ai/openapi/_original/atako-ai-api-openapi.json
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Customer is a legal entity or a natural person of legal age acting in the course of their professional activity.
    type: business
  - text: The Service is intended for professionals. It is not offered to consumers and may not be subscribed to for personal use.
    type: individual
  minimum_age:
    text: The Customer is a legal entity or a natural person of legal age acting in the course of their professional activity.
    value: of legal age
  restricted_uses:
  - summary: Prohibited uses listed in Article 8.2
    text: 'It is prohibited to use the Platform or the Agents to: generate or disseminate content that is unlawful, hateful, defamatory or obscene'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration requires accurate and complete information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atako
provenance_date: '2026-11-09'
provider_name: Atako
provider_slug: atako-ai
slug: atako-ai-eligibility
source_date: '2026-11-09'
source_filename: atako-ai-eligibility.yml
source_heading: Eligibility
source_page: https://atako.ai/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atako\naid: atako-ai\nurl: https://atako.ai/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Customer is a legal entity or a natural person of legal age acting in the course of their professional\n    activity.\n- type: individual\n  text: The Service is intended for professionals. It is not offered to consumers and may not be subscribed to for\n    personal use.\nrestricted_uses:\n- summary: Prohibited uses listed in Article 8.2\n  text: 'It is prohibited to use the Platform or the Agents to: generate or disseminate content\
  \ that is unlawful,\n    hateful, defamatory or obscene'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration requires accurate and complete information.\nminimum_age:\n  value: of legal age\n  text: The Customer is a legal entity or a natural person of legal age acting in the course of their professional\n    activity.\n"
source_yaml_url: https://artifacts.apis.io/atako-ai/eligibility/atako-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Atako's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Autonomous Agents
- Platform
- Software-as-a-Service
- Workforce
---
