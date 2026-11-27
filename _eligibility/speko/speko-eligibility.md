---
api_specs:
- filename: speko-agents-api-openapi.yml
  format: yaml
  label: Speko Agents API
  slug: speko-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-agents-api-openapi.yml
- filename: speko-providers-api-openapi.yml
  format: yaml
  label: Speko Providers API
  slug: speko-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-providers-api-openapi.yml
- filename: speko-telephony-api-openapi.yml
  format: yaml
  label: Speko Telephony API
  slug: speko-telephony-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-telephony-api-openapi.yml
- filename: speko-voice-api-openapi.yml
  format: yaml
  label: Speko Voice API
  slug: speko-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-voice-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Speko for an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data
    text: You should not submit regulated or highly sensitive data unless your Speko workspace and selected providers are configured for that use case.
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
name: Speko
provenance_date: '2026-11-10'
provider_name: Speko
provider_slug: speko
slug: speko-eligibility
source_date: '2026-11-10'
source_filename: speko-eligibility.yml
source_heading: Eligibility
source_page: https://speko.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Speko\naid: speko\nurl: https://speko.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Speko for an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: Sensitive data\n  text: You should not submit regulated or highly sensitive data unless your Speko workspace and selected providers\n    are configured for that use case.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/speko/eligibility/speko-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Speko's own page on 2026-11-10.
synthetic: false
tags:
- Voice
- Voice AI
- Speech-to-Text
- Text-to-Speech
- LLM
- Telephony
- API Gateway
- Conversational AI
- Developer Tools
- AI Infrastructure
---
