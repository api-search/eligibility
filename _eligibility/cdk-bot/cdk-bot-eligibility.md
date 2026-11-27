---
api_specs:
- filename: cdk-bot-games-api-openapi.yml
  format: yaml
  label: CDK Bot Games API
  slug: cdk-bot-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdk-bot/openapi/cdk-bot-games-api-openapi.yml
- filename: cdk-bot-meta-api-openapi.yml
  format: yaml
  label: CDK Bot Meta API
  slug: cdk-bot-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdk-bot/openapi/cdk-bot-meta-api-openapi.yml
- filename: cdk-bot-orders-api-openapi.yml
  format: yaml
  label: CDK Bot Orders API
  slug: cdk-bot-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdk-bot/openapi/cdk-bot-orders-api-openapi.yml
- filename: cdk-bot-purchase-api-openapi.yml
  format: yaml
  label: CDK Bot Purchase API
  slug: cdk-bot-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdk-bot/openapi/cdk-bot-purchase-api-openapi.yml
- filename: cdk-bot-refunds-api-openapi.yml
  format: yaml
  label: CDK Bot Refunds API
  slug: cdk-bot-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdk-bot/openapi/cdk-bot-refunds-api-openapi.yml
- filename: cdk-bot-status-api-openapi.yml
  format: yaml
  label: CDK Bot Status API
  slug: cdk-bot-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdk-bot/openapi/cdk-bot-status-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use this service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use this service.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: CDK Bot does not require user registration or collect personal information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CDK Bot
provenance_date: '2026-11-09'
provider_name: CDK Bot
provider_slug: cdk-bot
slug: cdk-bot-eligibility
source_date: '2026-11-09'
source_filename: cdk-bot-eligibility.yml
source_heading: Eligibility
source_page: https://cdk.bot/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CDK Bot\naid: cdk-bot\nurl: https://cdk.bot/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use this service.\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: CDK Bot does not require user registration or collect personal information.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use this service.\n"
source_yaml_url: https://artifacts.apis.io/cdk-bot/eligibility/cdk-bot-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from CDK Bot's own page on 2026-11-09.
synthetic: false
tags:
- Digital Products
- Crypto Payments
- Autonomous Agents
---
