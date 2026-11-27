---
api_specs:
- filename: hilos-contact-api-openapi.yml
  format: yaml
  label: Hilos Contact API
  slug: hilos-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilos/openapi/hilos-contact-api-openapi.yml
- filename: hilos-conversation-api-openapi.yml
  format: yaml
  label: Hilos Conversation API
  slug: hilos-conversation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilos/openapi/hilos-conversation-api-openapi.yml
- filename: hilos-flow-execution-api-openapi.yml
  format: yaml
  label: Hilos Flow Execution API
  slug: hilos-flow-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilos/openapi/hilos-flow-execution-api-openapi.yml
- filename: hilos-flow-execution-contact-api-openapi.yml
  format: yaml
  label: Hilos Flow Execution Contact API
  slug: hilos-flow-execution-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilos/openapi/hilos-flow-execution-contact-api-openapi.yml
- filename: hilos-user-api-openapi.yml
  format: yaml
  label: Hilos User API
  slug: hilos-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilos/openapi/hilos-user-api-openapi.yml
- filename: hilos-whats-app-api-openapi.yml
  format: yaml
  label: Hilos Whats App API
  slug: hilos-whats-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilos/openapi/hilos-whats-app-api-openapi.yml
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
  - summary: Sensitive or child personal data not to be submitted
    text: 'Customer shall not (and shall not permit Data Subject to) disclose to Hilos any of the following categories of data: (i) any “sensitive” or “special categories” of Personal Data'
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
name: Hilos
provenance_date: '2026-11-09'
provider_name: Hilos
provider_slug: hilos
slug: hilos-eligibility
source_date: '2026-11-09'
source_filename: hilos-eligibility.yml
source_heading: Eligibility
source_page: https://hilos.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hilos\naid: hilos\nurl: https://hilos.io/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive or child personal data not to be submitted\n  text: 'Customer shall not (and shall not permit Data Subject to) disclose to Hilos any of the following categories\n    of data: (i) any “sensitive” or “special categories” of Personal Data'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hilos/eligibility/hilos-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Hilos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- WhatsApp
- Messaging
- Automation
- CRM
- Conversational Commerce
- Chatbots
- Customer Engagement
- Marketing
- A2A
---
