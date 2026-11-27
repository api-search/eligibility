---
api_specs:
- filename: entergram-accounts-api-openapi.yml
  format: yaml
  label: Entergram Accounts API
  slug: entergram-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-accounts-api-openapi.yml
- filename: entergram-chat-commands-api-openapi.yml
  format: yaml
  label: Entergram Chat Commands API
  slug: entergram-chat-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-chat-commands-api-openapi.yml
- filename: entergram-chats-api-openapi.yml
  format: yaml
  label: Entergram Chats API
  slug: entergram-chats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-chats-api-openapi.yml
- filename: entergram-contacts-api-openapi.yml
  format: yaml
  label: Entergram Contacts API
  slug: entergram-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-contacts-api-openapi.yml
- filename: entergram-custom-fields-api-openapi.yml
  format: yaml
  label: Entergram Custom Fields API
  slug: entergram-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-custom-fields-api-openapi.yml
- filename: entergram-events-api-openapi.yml
  format: yaml
  label: Entergram Events API
  slug: entergram-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-events-api-openapi.yml
- filename: entergram-groups-api-openapi.yml
  format: yaml
  label: Entergram Groups API
  slug: entergram-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-groups-api-openapi.yml
- filename: entergram-live-chats-api-openapi.yml
  format: yaml
  label: Entergram Live Chats API
  slug: entergram-live-chats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-live-chats-api-openapi.yml
- filename: entergram-make-webhooks-api-openapi.yml
  format: yaml
  label: Entergram Make webhooks API
  slug: entergram-make-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-make-webhooks-api-openapi.yml
- filename: entergram-members-api-openapi.yml
  format: yaml
  label: Entergram Members API
  slug: entergram-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-members-api-openapi.yml
- filename: entergram-messages-api-openapi.yml
  format: yaml
  label: Entergram Messages API
  slug: entergram-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-messages-api-openapi.yml
- filename: entergram-system-api-openapi.yml
  format: yaml
  label: Entergram System API
  slug: entergram-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-system-api-openapi.yml
- filename: entergram-tickets-api-openapi.yml
  format: yaml
  label: Entergram Tickets API
  slug: entergram-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-tickets-api-openapi.yml
- filename: entergram-webhooks-api-openapi.yml
  format: yaml
  label: Entergram Webhooks API
  slug: entergram-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-webhooks-api-openapi.yml
- filename: entergram-workspace-api-openapi.yml
  format: yaml
  label: Entergram Workspace API
  slug: entergram-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-workspace-api-openapi.yml
- filename: entergram-workspace-chats-api-openapi.yml
  format: yaml
  label: Entergram Workspace Chats API
  slug: entergram-workspace-chats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entergram/openapi/entergram-workspace-chats-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    - RU
    - BY
    served: []
    text: You may not use the Service if you are located or established in Iran, North Korea, or the occupied regions of Ukraine. You also may not use it if you are a company, organisation, or government body established in Russia or Belarus
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into binding agreements.
    type: individual
  - text: If you use the Service for business purposes, you agree to indemnify, defend, and hold harmless Entergram
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into binding agreements.
    value: '18'
  restricted_uses:
  - summary: Broadcasts and outreach compliance
    text: You are solely responsible for having a lawful basis to contact each recipient, for honouring opt-outs and exclusion lists
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- KP
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Entergram
provenance_date: '2026-11-09'
provider_name: Entergram
provider_slug: entergram
slug: entergram-eligibility
source_date: '2026-11-09'
source_filename: entergram-eligibility.yml
source_heading: Eligibility
source_page: https://www.entergram.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Entergram\naid: entergram\nurl: https://www.entergram.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - KP\n  - RU\n  - BY\n  text: You may not use the Service if you are located or established in Iran, North Korea, or the occupied regions\n    of Ukraine. You also may not use it if you are a company, organisation, or government body established in Russia\n    or Belarus\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into binding agreements.\n- type: business\n  text: If you use the Service for business purposes,\
  \ you agree to indemnify, defend, and hold harmless Entergram\nrestricted_uses:\n- summary: Broadcasts and outreach compliance\n  text: You are solely responsible for having a lawful basis to contact each recipient, for honouring opt-outs and\n    exclusion lists\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into binding agreements.\n"
source_yaml_url: https://artifacts.apis.io/entergram/eligibility/entergram-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Entergram's own page on 2026-11-09.
synthetic: false
tags:
- Messaging
- Notification
- Communications
- CRM
- Telegram
- Customer Service
- Ticketing
- Sales
- MCP
- Webhook
---
