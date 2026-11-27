---
api_specs:
- filename: chatley-ai-openapi-generated.yml
  format: yaml
  label: Chatley Developer API
  slug: developer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatley-ai/openapi/_ae-authored/chatley-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a legally binding contract to use our Services.
    type: individual
  - text: If you are using the Services on behalf of a company, organization, or other entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old
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
name: Chatley AI
provenance_date: '2026-11-09'
provider_name: Chatley AI
provider_slug: chatley-ai
slug: chatley-ai-eligibility
source_date: '2026-11-09'
source_filename: chatley-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.chatley.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chatley AI\naid: chatley-ai\nurl: https://www.chatley.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a legally binding contract to use our Services.\n- type: business\n  text: If you are using the Services on behalf of a company, organization, or other entity, you represent and warrant\n    that you have the authority to bind that entity to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/chatley-ai/eligibility/chatley-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Chatley AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice Agents
- Conversational AI
- AI Receptionist
- Telephony
- SMS
- White Label
- MCP
- Lead Generation
---
