---
api_specs:
- filename: smartlead-ai-campaign-statistics-api-openapi.yml
  format: yaml
  label: Smartlead Campaign Statistics API
  slug: smartlead-ai-campaign-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-campaign-statistics-api-openapi.yml
- filename: smartlead-ai-campaigns-api-openapi.yml
  format: yaml
  label: Smartlead Campaigns API
  slug: smartlead-ai-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-campaigns-api-openapi.yml
- filename: smartlead-ai-analytics-api-openapi.yml
  format: yaml
  label: Smartlead Analytics API
  slug: smartlead-ai-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-analytics-api-openapi.yml
- filename: smartlead-ai-authentication-api-openapi.yml
  format: yaml
  label: Smartlead Authentication API
  slug: smartlead-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-authentication-api-openapi.yml
- filename: smartlead-ai-email-accounts-api-openapi.yml
  format: yaml
  label: Smartlead Email Accounts API
  slug: smartlead-ai-email-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-email-accounts-api-openapi.yml
- filename: smartlead-ai-leads-api-openapi.yml
  format: yaml
  label: Smartlead Leads API
  slug: smartlead-ai-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-leads-api-openapi.yml
- filename: smartlead-ai-master-inbox-api-openapi.yml
  format: yaml
  label: Smartlead Master Inbox API
  slug: smartlead-ai-master-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-master-inbox-api-openapi.yml
- filename: smartlead-ai-smart-delivery-api-openapi.yml
  format: yaml
  label: Smartlead Smart Delivery API
  slug: smartlead-ai-smart-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-smart-delivery-api-openapi.yml
- filename: smartlead-ai-smart-senders-api-openapi.yml
  format: yaml
  label: Smartlead Smart Senders API
  slug: smartlead-ai-smart-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-smart-senders-api-openapi.yml
- filename: smartlead-ai-utilities-api-openapi.yml
  format: yaml
  label: Smartlead Utilities API
  slug: smartlead-ai-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-utilities-api-openapi.yml
- filename: smartlead-ai-webhooks-api-openapi.yml
  format: yaml
  label: Smartlead Webhooks API
  slug: smartlead-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartlead-ai/openapi/smartlead-ai-webhooks-api-openapi.yml
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
  - summary: Unsolicited messages and calls
    text: any use of the Service for the purpose of sending unsolicited commercial electronic messages or making unsolicited phonecalls, as defined by the Spam Laws is strictly prohibited
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
name: Smartlead
provenance_date: '2026-11-10'
provider_name: Smartlead
provider_slug: smartlead-ai
slug: smartlead-ai-eligibility
source_date: '2026-11-10'
source_filename: smartlead-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.smartlead.ai/new-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smartlead\naid: smartlead-ai\nurl: https://www.smartlead.ai/new-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited messages and calls\n  text: any use of the Service for the purpose of sending unsolicited commercial electronic messages or making unsolicited\n    phonecalls, as defined by the Spam Laws is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smartlead-ai/eligibility/smartlead-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Smartlead's own page on 2026-11-10.
synthetic: false
tags:
- Cold Email
- Outbound
- Sales
- Deliverability
- Email Warm-up
- Automation
- Sequences
- A2A
---
