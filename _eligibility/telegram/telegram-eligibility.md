---
api_specs:
- filename: telegram-bot-info-api-openapi.yml
  format: yaml
  label: Telegram Bot Info API
  slug: telegram-bot-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-bot-info-api-openapi.yml
- filename: telegram-chat-management-api-openapi.yml
  format: yaml
  label: Telegram Chat Management API
  slug: telegram-chat-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-chat-management-api-openapi.yml
- filename: telegram-getting-updates-api-openapi.yml
  format: yaml
  label: Telegram Getting Updates API
  slug: telegram-getting-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-getting-updates-api-openapi.yml
- filename: telegram-invites-api-openapi.yml
  format: yaml
  label: Telegram Invites API
  slug: telegram-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-invites-api-openapi.yml
- filename: telegram-member-management-api-openapi.yml
  format: yaml
  label: Telegram Member Management API
  slug: telegram-member-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-member-management-api-openapi.yml
- filename: telegram-message-editing-api-openapi.yml
  format: yaml
  label: Telegram Message Editing API
  slug: telegram-message-editing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-message-editing-api-openapi.yml
- filename: telegram-messaging-api-openapi.yml
  format: yaml
  label: Telegram Messaging API
  slug: telegram-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-messaging-api-openapi.yml
- filename: telegram-payments-api-openapi.yml
  format: yaml
  label: Telegram Payments API
  slug: telegram-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-payments-api-openapi.yml
- filename: telegram-stickers-api-openapi.yml
  format: yaml
  label: Telegram Stickers API
  slug: telegram-stickers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-stickers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Users in EU countries, the United Kingdom and Australia must be at least 18 years old to sign up.
    value: '18'
  restricted_uses:
  - summary: illegal goods and services
    text: Engage in activities that are recognized as illegal in the majority of countries.
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
name: Telegram
provenance_date: '2026-11-10'
provider_name: Telegram
provider_slug: telegram
slug: telegram-eligibility
source_date: '2026-11-10'
source_filename: telegram-eligibility.yml
source_heading: Eligibility
source_page: https://telegram.org/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Telegram\naid: telegram\nurl: https://telegram.org/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: illegal goods and services\n  text: Engage in activities that are recognized as illegal in the majority of countries.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users in EU countries, the United Kingdom and Australia must be at least 18 years old to sign up.\n"
source_yaml_url: https://artifacts.apis.io/telegram/eligibility/telegram-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Telegram's own page on 2026-11-10.
synthetic: false
tags:
- Bots
- Chat
- Messaging
- Notification
- Payments
- Telegram
- Social
- Public APIs
- Chatbots
- Webhook
- Mini Apps
---
