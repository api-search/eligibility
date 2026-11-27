---
api_specs:
- filename: callchatsyn-com-answer-api-openapi.yml
  format: yaml
  label: CallChatSyn Answer API
  slug: callchatsyn-com-answer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callchatsyn-com/openapi/callchatsyn-com-answer-api-openapi.yml
- filename: callchatsyn-com-bookings-api-openapi.yml
  format: yaml
  label: CallChatSyn Bookings API
  slug: callchatsyn-com-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callchatsyn-com/openapi/callchatsyn-com-bookings-api-openapi.yml
- filename: callchatsyn-com-slots-api-openapi.yml
  format: yaml
  label: CallChatSyn Slots API
  slug: callchatsyn-com-slots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callchatsyn-com/openapi/callchatsyn-com-slots-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're signing up on behalf of a business, you're confirming you have authority to bind that business to them.
    type: business
  minimum_age:
    text: You must be old enough to enter a binding contract in your jurisdiction to sign up.
    value: null
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
name: CallChatSyn
provenance_date: '2026-11-09'
provider_name: CallChatSyn
provider_slug: callchatsyn-com
slug: callchatsyn-com-eligibility
source_date: '2026-11-09'
source_filename: callchatsyn-com-eligibility.yml
source_heading: Eligibility
source_page: https://callchatsyn.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallChatSyn\naid: callchatsyn-com\nurl: https://callchatsyn.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're signing up on behalf of a business, you're confirming you have authority to bind that business\n    to them.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to enter a binding contract in your jurisdiction to sign up.\n"
source_yaml_url: https://artifacts.apis.io/callchatsyn-com/eligibility/callchatsyn-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from CallChatSyn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Receptionist
- Answering Service
- Voice AI
- Appointment Booking
- Chatbots
- WhatsApp
- Small Business
- MCP
---
