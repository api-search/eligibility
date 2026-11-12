---
api_specs:
- filename: corebee-ai-auth-api-openapi.yml
  format: yaml
  label: Corebee Auth API
  slug: corebee-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-auth-api-openapi.yml
- filename: corebee-ai-contacts-api-openapi.yml
  format: yaml
  label: Corebee Contacts API
  slug: corebee-ai-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-contacts-api-openapi.yml
- filename: corebee-ai-conversations-api-openapi.yml
  format: yaml
  label: Corebee Conversations API
  slug: corebee-ai-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-conversations-api-openapi.yml
- filename: corebee-ai-labels-api-openapi.yml
  format: yaml
  label: Corebee Labels API
  slug: corebee-ai-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-labels-api-openapi.yml
- filename: corebee-ai-voice-api-openapi.yml
  format: yaml
  label: Corebee Voice API
  slug: corebee-ai-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-voice-api-openapi.yml
- filename: corebee-ai-webhooks-api-openapi.yml
  format: yaml
  label: Corebee Webhooks API
  slug: corebee-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is designed for businesses of all sizes, including agencies and BPOs.
    type: business
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited AI decision uses
    text: Use AI features for biometric identification, emotional recognition, creditworthiness assessment, or employment decision-making
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
name: Corebee
provenance_date: '2026-11-09'
provider_name: Corebee
provider_slug: corebee-ai
slug: corebee-ai-eligibility
source_date: '2026-11-09'
source_filename: corebee-ai-eligibility.yml
source_heading: Eligibility
source_page: https://corebee.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corebee\naid: corebee-ai\nurl: https://corebee.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is designed for businesses of all sizes, including agencies and BPOs.\nrestricted_uses:\n- summary: Prohibited AI decision uses\n  text: Use AI features for biometric identification, emotional recognition, creditworthiness assessment, or employment\n    decision-making\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/corebee-ai/eligibility/corebee-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Corebee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Support
- Artificial Intelligence
- Chatbots
- Help Desk
- Omnichannel Messaging
- Voice Agents
- MCP
---
