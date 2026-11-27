---
api_specs:
- filename: sendspark-dvm-bundles-api-openapi.yml
  format: yaml
  label: Sendspark DVM Bundles API
  slug: sendspark-dvm-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-dvm-bundles-api-openapi.yml
- filename: sendspark-dynamics-campaign-api-openapi.yml
  format: yaml
  label: Sendspark Dynamics Campaign API
  slug: sendspark-dynamics-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-dynamics-campaign-api-openapi.yml
- filename: sendspark-webhook-api-openapi.yml
  format: yaml
  label: Sendspark Webhook API
  slug: sendspark-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-webhook-api-openapi.yml
- filename: sendspark-workspace-api-openapi.yml
  format: yaml
  label: Sendspark Workspace API
  slug: sendspark-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-workspace-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individuals or companies (“Customers”)
    type: business
  minimum_age:
    text: The Service is not directed to individuals under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Not a competitor
    text: you, and if applicable the business or entity that you represent on the Service, are/is not a competitor of ours.
  - summary: Biometric features require opt-in
    text: We will create a Voiceprint, and scan face geometry, only where the individual concerned has affirmatively enabled the relevant feature and agreed to our Biometric Information Notice and Consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the completion or acknowledgment of setting up any Payment Method.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sendspark
provenance_date: '2026-11-10'
provider_name: Sendspark
provider_slug: sendspark
slug: sendspark-eligibility
source_date: '2026-11-10'
source_filename: sendspark-eligibility.yml
source_heading: Eligibility
source_page: https://www.sendspark.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sendspark\naid: sendspark\nurl: https://www.sendspark.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: individuals or companies (“Customers”)\nrestricted_uses:\n- summary: Not a competitor\n  text: you, and if applicable the business or entity that you represent on the Service, are/is not a competitor\n    of ours.\n- summary: Biometric features require opt-in\n  text: We will create a Voiceprint, and scan face geometry, only where the individual concerned has affirmatively\n    enabled the relevant feature and agreed to our\
  \ Biometric Information Notice and Consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information may be required prior to the completion or acknowledgment of setting up any\n    Payment Method.\nminimum_age:\n  value: '13'\n  text: The Service is not directed to individuals under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/sendspark/eligibility/sendspark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sendspark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Sales
- Marketing
- Personalization
- Artificial Intelligence
- Video Messaging
- Webhook
- MCP
- A2A
---
