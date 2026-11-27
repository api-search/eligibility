---
api_specs:
- filename: icallagent-public-api-agents-api-openapi.yml
  format: yaml
  label: iCallAgent Public API Agents API
  slug: icallagent-public-api-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icallagent-public-api/openapi/icallagent-public-api-agents-api-openapi.yml
- filename: icallagent-public-api-campaigns-api-openapi.yml
  format: yaml
  label: iCallAgent Public API Campaigns API
  slug: icallagent-public-api-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icallagent-public-api/openapi/icallagent-public-api-campaigns-api-openapi.yml
- filename: icallagent-public-api-contacts-api-openapi.yml
  format: yaml
  label: iCallAgent Public API Contacts API
  slug: icallagent-public-api-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icallagent-public-api/openapi/icallagent-public-api-contacts-api-openapi.yml
- filename: icallagent-public-api-phone-numbers-api-openapi.yml
  format: yaml
  label: iCallAgent Public API Phone Numbers API
  slug: icallagent-public-api-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icallagent-public-api/openapi/icallagent-public-api-phone-numbers-api-openapi.yml
- filename: icallagent-public-api-webhooks-api-openapi.yml
  format: yaml
  label: iCallAgent Public API Webhooks API
  slug: icallagent-public-api-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/icallagent-public-api/openapi/icallagent-public-api-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unsolicited telemarketing or unlawful robocalling
    text: You must not Use the Service for unsolicited telemarketing, unlawful robocalling, or any workflow that lacks the required consent or notices.
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
name: iCallAgent Public API
provenance_date: '2026-11-09'
provider_name: iCallAgent Public API
provider_slug: icallagent-public-api
slug: icallagent-public-api-eligibility
source_date: '2026-11-09'
source_filename: icallagent-public-api-eligibility.yml
source_heading: Eligibility
source_page: https://icallagent.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iCallAgent Public API\naid: icallagent-public-api\nurl: https://icallagent.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited telemarketing or unlawful robocalling\n  text: You must not Use the Service for unsolicited telemarketing, unlawful robocalling, or any workflow that lacks\n    the required consent or notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/icallagent-public-api/eligibility/icallagent-public-api-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from iCallAgent Public API's own page on 2026-11-09.
synthetic: false
tags:
- Voice AI
- voice ai assistant
- Conversational AI
- Voice Agents
- telephony / CPaaS
- contact center / CCaaS
- Outbound Calling
- speech (ASR/TTS)
- agent tools / MCP
---
