---
api_specs:
- filename: sail-research-batches-api-api-openapi.yml
  format: yaml
  label: Sail Research Batches API
  slug: sail-research-batches-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sail-research/openapi/sail-research-batches-api-api-openapi.yml
- filename: sail-research-chat-completions-api-api-openapi.yml
  format: yaml
  label: Sail Research Chat Completions API
  slug: sail-research-chat-completions-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sail-research/openapi/sail-research-chat-completions-api-api-openapi.yml
- filename: sail-research-messages-api-api-openapi.yml
  format: yaml
  label: Sail Research Messages API
  slug: sail-research-messages-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sail-research/openapi/sail-research-messages-api-api-openapi.yml
- filename: sail-research-models-api-api-openapi.yml
  format: yaml
  label: Sail Research Models API
  slug: sail-research-models-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sail-research/openapi/sail-research-models-api-api-openapi.yml
- filename: sail-research-responses-api-api-openapi.yml
  format: yaml
  label: Sail Research Responses API
  slug: sail-research-responses-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sail-research/openapi/sail-research-responses-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Services are intended and made available solely for use by businesses and enterprises for their internal business purposes, and not for personal, family, household, or other consumer purposes
    type: business
  minimum_age:
    text: You represent and warrant that you are at least 18 years old and able to form a legally binding contract.
    value: '18'
  restricted_uses:
  - summary: Prohibited content categories
    text: (d) sensitive personal data or special-category data under applicable law; (e) personal data of individuals under 16
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
name: Sail Research
provenance_date: '2026-11-10'
provider_name: Sail Research
provider_slug: sail-research
slug: sail-research-eligibility
source_date: '2026-11-10'
source_filename: sail-research-eligibility.yml
source_heading: Eligibility
source_page: https://www.sailresearch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sail Research\naid: sail-research\nurl: https://www.sailresearch.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the Services are intended and made available solely for use by businesses and enterprises for their internal\n    business purposes, and not for personal, family, household, or other consumer purposes\nrestricted_uses:\n- summary: Prohibited content categories\n  text: (d) sensitive personal data or special-category data under applicable law; (e) personal data of individuals\n    under 16\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years old and able to form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/sail-research/eligibility/sail-research-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sail Research's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Inference
- Agents
- Machine Learning
- Developer Tools
- Open Source Models
- Infrastructure
---
