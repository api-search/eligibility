---
api_specs:
- filename: kimi-ai-batch-api-openapi.yml
  format: yaml
  label: Moonshot AI Batch API
  slug: kimi-ai-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-batch-api-openapi.yml
- filename: kimi-ai-billing-api-openapi.yml
  format: yaml
  label: Moonshot AI Billing API
  slug: kimi-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-billing-api-openapi.yml
- filename: kimi-ai-files-api-openapi.yml
  format: yaml
  label: Moonshot AI Files API
  slug: kimi-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-files-api-openapi.yml
- filename: kimi-ai-models-api-openapi.yml
  format: yaml
  label: Moonshot AI Models API
  slug: kimi-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-models-api-openapi.yml
- filename: kimi-ai-utilities-api-openapi.yml
  format: yaml
  label: Moonshot AI Utilities API
  slug: kimi-ai-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-utilities-api-openapi.yml
- filename: kimi-ai-responses-api-openapi.yml
  format: yaml
  label: Moonshot AI Responses API
  slug: kimi-ai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-responses-api-openapi.yml
- filename: kimi-ai-tools-api-openapi.yml
  format: yaml
  label: Moonshot AI Tools API
  slug: kimi-ai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-tools-api-openapi.yml
- filename: kimi-ai-messages-api-openapi.yml
  format: yaml
  label: Kimi (Moonshot AI) Messages API
  slug: kimi-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-messages-api-openapi.yml
- filename: kimi-ai-chat-completions-api-openapi.yml
  format: yaml
  label: Kimi (Moonshot AI) Chat Completions API
  slug: kimi-ai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kimi-ai/openapi/kimi-ai-chat-completions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You should not be the subject of any trade restrictions, sanctions, or other legal or regulatory restrictions imposed by any country, international organization, or region.
  entity_types:
  - text: To use the Services as an individual, you must be at least 18 years old or the minimum age required by your country to consent to such use.
    type: individual
  - text: If the account is used for enterprise, you must ensure that you have authorization from the business.
    type: business
  minimum_age:
    text: To use the Services as an individual, you must be at least 18 years old or the minimum age required by your country to consent to such use.
    value: '18'
  restricted_uses:
  - summary: Decisions with legal or material impact on individuals
    text: You must not use any output relating to a person for any purpose that could have a legal or material impact on that person
  - summary: Protected Health Information
    text: You commit to not utilizing the Services for the creation, reception, maintenance, transmission, or any other processing of information that encompasses or qualifies as “Protected Health Information”
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
name: Kimi (Moonshot AI)
provenance_date: '2026-11-09'
provider_name: Kimi (Moonshot AI)
provider_slug: kimi-ai
slug: kimi-ai-eligibility
source_date: '2026-11-09'
source_filename: kimi-ai-eligibility.yml
source_heading: Eligibility
source_page: https://platform.kimi.ai/docs/agreement/modeluse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kimi (Moonshot AI)\naid: kimi-ai\nurl: https://platform.kimi.ai/docs/agreement/modeluse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You should not be the subject of any trade restrictions, sanctions, or other legal or regulatory restrictions\n    imposed by any country, international organization, or region.\nentity_types:\n- type: individual\n  text: To use the Services as an individual, you must be at least 18 years old or the minimum age required by your\n    country to consent to such use.\n- type: business\n  text: If the account is used for enterprise, you must ensure that\
  \ you have authorization from the business.\nrestricted_uses:\n- summary: Decisions with legal or material impact on individuals\n  text: You must not use any output relating to a person for any purpose that could have a legal or material impact\n    on that person\n- summary: Protected Health Information\n  text: You commit to not utilizing the Services for the creation, reception, maintenance, transmission, or any\n    other processing of information that encompasses or qualifies as “Protected Health Information”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Services as an individual, you must be at least 18 years old or the minimum age required by your\n    country to consent to such use.\n"
source_yaml_url: https://artifacts.apis.io/kimi-ai/eligibility/kimi-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Kimi (Moonshot AI)'s own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Inference
- Long Context
- Kimi
- Foundation Models
---
