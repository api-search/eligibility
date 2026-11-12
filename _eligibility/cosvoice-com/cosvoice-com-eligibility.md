---
api_specs:
- filename: cosvoice-com-activity-api-openapi.yml
  format: yaml
  label: CosVoice Activity API
  slug: cosvoice-com-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-activity-api-openapi.yml
- filename: cosvoice-com-calls-api-openapi.yml
  format: yaml
  label: CosVoice Calls API
  slug: cosvoice-com-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-calls-api-openapi.yml
- filename: cosvoice-com-contacts-api-openapi.yml
  format: yaml
  label: CosVoice Contacts API
  slug: cosvoice-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-contacts-api-openapi.yml
- filename: cosvoice-com-emails-api-openapi.yml
  format: yaml
  label: CosVoice Emails API
  slug: cosvoice-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-emails-api-openapi.yml
- filename: cosvoice-com-history-api-openapi.yml
  format: yaml
  label: CosVoice History API
  slug: cosvoice-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-history-api-openapi.yml
- filename: cosvoice-com-line-api-openapi.yml
  format: yaml
  label: CosVoice Line API
  slug: cosvoice-com-line-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-line-api-openapi.yml
- filename: cosvoice-com-messages-api-openapi.yml
  format: yaml
  label: CosVoice Messages API
  slug: cosvoice-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-messages-api-openapi.yml
- filename: cosvoice-com-reservations-api-openapi.yml
  format: yaml
  label: CosVoice Reservations API
  slug: cosvoice-com-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-reservations-api-openapi.yml
- filename: cosvoice-com-settings-api-openapi.yml
  format: yaml
  label: CosVoice Settings API
  slug: cosvoice-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-settings-api-openapi.yml
- filename: cosvoice-com-webhook-api-openapi.yml
  format: yaml
  label: CosVoice Webhook API
  slug: cosvoice-com-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-webhook-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Lines place calls and send texts to US and Canada numbers only
  entity_types:
  - text: You must be 18 or older
    type: individual
  - text: use the service for your own or your organisation's legitimate purposes
    type: business
  minimum_age:
    text: You must be 18 or older
    value: '18'
  restricted_uses:
  - summary: No payments or professional advice
    text: The line never makes payments and does not provide legal, medical, or financial advice.
  - summary: No emergency services
    text: Do not use a line for unsolicited marketing, robocalling, harassment, impersonation of a specific person, emergency services, or anything unlawful.
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
name: CosVoice
provenance_date: '2026-11-09'
provider_name: CosVoice
provider_slug: cosvoice-com
slug: cosvoice-com-eligibility
source_date: '2026-11-09'
source_filename: cosvoice-com-eligibility.yml
source_heading: Eligibility
source_page: https://cosvoice.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CosVoice\naid: cosvoice-com\nurl: https://cosvoice.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Lines place calls and send texts to US and Canada numbers only\nentity_types:\n- type: individual\n  text: You must be 18 or older\n- type: business\n  text: use the service for your own or your organisation's legitimate purposes\nrestricted_uses:\n- summary: No payments or professional advice\n  text: The line never makes payments and does not provide legal, medical, or financial advice.\n- summary: No emergency services\n  text: Do not use a line for unsolicited\
  \ marketing, robocalling, harassment, impersonation of a specific person,\n    emergency services, or anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older\n"
source_yaml_url: https://artifacts.apis.io/cosvoice-com/eligibility/cosvoice-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from CosVoice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Voice
- Telephony
- Phone Numbers
- AI Receptionist
- Call Transcription
- MCP
- Small Business
---
