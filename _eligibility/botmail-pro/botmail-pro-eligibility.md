---
api_specs:
- filename: botmail-pro-account-api-openapi.yml
  format: yaml
  label: Botmail Account API
  slug: botmail-pro-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-account-api-openapi.yml
- filename: botmail-pro-billing-api-openapi.yml
  format: yaml
  label: Botmail Billing API
  slug: botmail-pro-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-billing-api-openapi.yml
- filename: botmail-pro-claim-api-openapi.yml
  format: yaml
  label: Botmail Claim API
  slug: botmail-pro-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-claim-api-openapi.yml
- filename: botmail-pro-events-api-openapi.yml
  format: yaml
  label: Botmail Events API
  slug: botmail-pro-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-events-api-openapi.yml
- filename: botmail-pro-keys-api-openapi.yml
  format: yaml
  label: Botmail Keys API
  slug: botmail-pro-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-keys-api-openapi.yml
- filename: botmail-pro-mail-api-openapi.yml
  format: yaml
  label: Botmail Mail API
  slug: botmail-pro-mail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-mail-api-openapi.yml
- filename: botmail-pro-mailboxes-api-openapi.yml
  format: yaml
  label: Botmail Mailboxes API
  slug: botmail-pro-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-mailboxes-api-openapi.yml
- filename: botmail-pro-meta-api-openapi.yml
  format: yaml
  label: Botmail Meta API
  slug: botmail-pro-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-meta-api-openapi.yml
- filename: botmail-pro-send-api-openapi.yml
  format: yaml
  label: Botmail Send API
  slug: botmail-pro-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-send-api-openapi.yml
- filename: botmail-pro-webhooks-api-openapi.yml
  format: yaml
  label: Botmail Webhooks API
  slug: botmail-pro-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 (or the age of majority where you live) and able to form a contract.
    type: individual
  minimum_age:
    text: You must be at least 18 (or the age of majority where you live) and able to form a contract.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a supported provider (currently GitHub).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Botmail
provenance_date: '2026-11-09'
provider_name: Botmail
provider_slug: botmail-pro
slug: botmail-pro-eligibility
source_date: '2026-11-09'
source_filename: botmail-pro-eligibility.yml
source_heading: Eligibility
source_page: https://botmail.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Botmail\naid: botmail-pro\nurl: https://botmail.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 (or the age of majority where you live) and able to form a contract.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a supported provider (currently GitHub).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (or the age of majority where you live) and able to form a contract.\n"
source_yaml_url: https://artifacts.apis.io/botmail-pro/eligibility/botmail-pro-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Botmail's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Email
- Messaging
- Automation
- Botmail
---
