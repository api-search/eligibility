---
api_specs:
- filename: Public-APIs
  format: yaml
  label: Kore.ai AI for Service Platform APIs
  slug: koreai-ai-for-service-platform-apis
  spec_type: Postman
  url: https://github.com/Koredotcom/Public-APIs
- filename: koreai-chat-api-openapi.yml
  format: yaml
  label: Kore.ai Chat API
  slug: koreai-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koreai/openapi/koreai-chat-api-openapi.yml
- filename: koreai-conversation-api-openapi.yml
  format: yaml
  label: Kore.ai Conversation API
  slug: koreai-conversation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koreai/openapi/koreai-conversation-api-openapi.yml
- filename: koreai-workflows-api-openapi.yml
  format: yaml
  label: Kore.ai Workflows API
  slug: koreai-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koreai/openapi/koreai-workflows-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are thirteen (13) years or older
    type: individual
  - text: If you are accessing and/or using the Services on behalf of any company, organization or any association of individuals
    type: business
  minimum_age:
    text: You may use the Services only if you are thirteen (13) years or older
    value: '13'
  restricted_uses:
  - summary: Barred users excluded
    text: are not barred from using the Services under applicable laws of the country from which you are accessing the Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you want to use the Services, whether for Individual Consumer Use, Team Use, or Enterprise Use, you will be required to create an account (“Account”).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kore.ai
provenance_date: '2026-11-09'
provider_name: Kore.ai
provider_slug: koreai
slug: koreai-eligibility
source_date: '2026-11-09'
source_filename: koreai-eligibility.yml
source_heading: Eligibility
source_page: https://www.kore.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kore.ai\naid: koreai\nurl: https://www.kore.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are thirteen (13) years or older\n- type: business\n  text: If you are accessing and/or using the Services on behalf of any company, organization or any association\n    of individuals\nrestricted_uses:\n- summary: Barred users excluded\n  text: are not barred from using the Services under applicable laws of the country from which you are accessing\n    the Services\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: If you want to use the Services, whether for Individual Consumer Use, Team Use, or Enterprise Use, you will\n    be required to create an account (“Account”).\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are thirteen (13) years or older\n"
source_yaml_url: https://artifacts.apis.io/koreai/eligibility/koreai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kore.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Conversational AI
- Agents
- Agent Platform
- Contact Center
- Customer Experience
- Employee Experience
- Voice
- Automation
- MCP
- Enterprise Software
---
