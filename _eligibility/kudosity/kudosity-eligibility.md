---
api_specs:
- filename: kudosity-account-api-openapi.yml
  format: yaml
  label: Kudosity Account API
  slug: kudosity-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-account-api-openapi.yml
- filename: kudosity-contacts-lists-api-openapi.yml
  format: yaml
  label: Kudosity Contacts & Lists API
  slug: kudosity-contacts-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-contacts-lists-api-openapi.yml
- filename: kudosity-email-sms-api-openapi.yml
  format: yaml
  label: Kudosity Email SMS API
  slug: kudosity-email-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-email-sms-api-openapi.yml
- filename: kudosity-keywords-api-openapi.yml
  format: yaml
  label: Kudosity Keywords API
  slug: kudosity-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-keywords-api-openapi.yml
- filename: kudosity-mms-api-openapi.yml
  format: yaml
  label: Kudosity MMS API
  slug: kudosity-mms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-mms-api-openapi.yml
- filename: kudosity-numbers-api-openapi.yml
  format: yaml
  label: Kudosity Numbers API
  slug: kudosity-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-numbers-api-openapi.yml
- filename: kudosity-rcs-api-openapi.yml
  format: yaml
  label: Kudosity RCS API
  slug: kudosity-rcs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-rcs-api-openapi.yml
- filename: kudosity-reporting-api-openapi.yml
  format: yaml
  label: Kudosity Reporting API
  slug: kudosity-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-reporting-api-openapi.yml
- filename: kudosity-senders-api-openapi.yml
  format: yaml
  label: Kudosity Senders API
  slug: kudosity-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-senders-api-openapi.yml
- filename: kudosity-sms-api-openapi.yml
  format: yaml
  label: Kudosity SMS API
  slug: kudosity-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-sms-api-openapi.yml
- filename: kudosity-webhook-api-openapi.yml
  format: yaml
  label: Kudosity Webhook API
  slug: kudosity-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-webhook-api-openapi.yml
- filename: kudosity-whats-app-api-openapi.yml
  format: yaml
  label: Kudosity Whats App API
  slug: kudosity-whats-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kudosity/openapi/kudosity-whats-app-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If an individual contracts as a sole trader, that individual is the Customer.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Breach of sanctions or export controls
    text: You must not use the Services in breach of applicable sanctions, trade controls or export-control laws
  - summary: Impersonation, fraud, scams
    text: to impersonate a person or entity or misrepresent the origin of a communication
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: If approved for post-pay Services, you must pay Fees and Taxes within the period specified
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kudosity
provenance_date: '2026-11-09'
provider_name: Kudosity
provider_slug: kudosity
slug: kudosity-eligibility
source_date: '2026-11-09'
source_filename: kudosity-eligibility.yml
source_heading: Eligibility
source_page: https://kudosity.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kudosity\naid: kudosity\nurl: https://kudosity.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If an individual contracts as a sole trader, that individual is the Customer.\nrestricted_uses:\n- summary: Breach of sanctions or export controls\n  text: You must not use the Services in breach of applicable sanctions, trade controls or export-control laws\n- summary: Impersonation, fraud, scams\n  text: to impersonate a person or entity or misrepresent the origin of a communication\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: If approved for post-pay Services, you must pay Fees and Taxes within the period specified\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kudosity/eligibility/kudosity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Kudosity's own page on 2026-11-09.
synthetic: false
tags:
- Messaging
- SMS
- MMS
- RCS
- WhatsApp
- Communications
- CPaaS
- Webhook
- MCP
- Agent-Native
- Australia
- Notification
- Two-Way Messaging
- Contact Management
---
