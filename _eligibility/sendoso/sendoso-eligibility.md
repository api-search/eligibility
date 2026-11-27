---
api_specs:
- filename: sendoso-marketplace-api-openapi.yml
  format: yaml
  label: Sendoso Marketplace and SmartSend API
  slug: sendoso-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-marketplace-api-openapi.yml
- filename: sendoso-webhooks-asyncapi.yml
  format: yaml
  label: Sendoso Webhooks
  slug: sendoso-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/sendoso/asyncapi/sendoso-webhooks-asyncapi.yml
- filename: sendoso-campaigns-api-openapi.yml
  format: yaml
  label: Sendoso Campaigns API
  slug: sendoso-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-campaigns-api-openapi.yml
- filename: sendoso-sends-api-openapi.yml
  format: yaml
  label: Sendoso Sends API
  slug: sendoso-sends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-sends-api-openapi.yml
- filename: sendoso-smartsend-api-openapi.yml
  format: yaml
  label: Sendoso Smart Send API
  slug: sendoso-smartsend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-smartsend-api-openapi.yml
- filename: sendoso-teams-api-openapi.yml
  format: yaml
  label: Sendoso Teams API
  slug: sendoso-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-teams-api-openapi.yml
- filename: sendoso-users-api-openapi.yml
  format: yaml
  label: Sendoso Users API
  slug: sendoso-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-users-api-openapi.yml
claim_count: 2
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
  - summary: Compliance with laws
    text: Customer will use the Service in compliance with all applicable laws and regulations
  - summary: Prohibited items
    text: 'Under no circumstances will Sendoso receive any of the below items:'
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
name: Sendoso
provenance_date: '2026-11-10'
provider_name: Sendoso
provider_slug: sendoso
slug: sendoso-eligibility
source_date: '2026-11-10'
source_filename: sendoso-eligibility.yml
source_heading: Eligibility
source_page: https://www.sendoso.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sendoso\naid: sendoso\nurl: https://www.sendoso.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Compliance with laws\n  text: Customer will use the Service in compliance with all applicable laws and regulations\n- summary: Prohibited items\n  text: 'Under no circumstances will Sendoso receive any of the below items:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sendoso/eligibility/sendoso-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Sendoso's own page on 2026-11-10.
synthetic: false
tags:
- Corporate Gifting
- Direct Mail
- Sales Engagement
- Marketing Automation
- CRM Integration
- eGifts
- Swag and Merchandise
- Fulfillment
- Employee Recognition
- Account Based Marketing
- SCIM Provisioning
- Webhook
- A2A
---
