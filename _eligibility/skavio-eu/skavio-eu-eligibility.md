---
api_specs:
- filename: skavio-eu-batch-processing-api-openapi.yml
  format: yaml
  label: skavio-eu Batch processing API
  slug: skavio-eu-batch-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-batch-processing-api-openapi.yml
- filename: skavio-eu-billing-api-openapi.yml
  format: yaml
  label: skavio-eu Billing API
  slug: skavio-eu-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-billing-api-openapi.yml
- filename: skavio-eu-bulk-manifests-api-openapi.yml
  format: yaml
  label: skavio-eu Bulk manifests API
  slug: skavio-eu-bulk-manifests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-bulk-manifests-api-openapi.yml
- filename: skavio-eu-contacts-api-openapi.yml
  format: yaml
  label: skavio-eu Contacts API
  slug: skavio-eu-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-contacts-api-openapi.yml
- filename: skavio-eu-events-api-openapi.yml
  format: yaml
  label: skavio-eu Events API
  slug: skavio-eu-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-events-api-openapi.yml
- filename: skavio-eu-flow-api-openapi.yml
  format: yaml
  label: skavio-eu Flow API
  slug: skavio-eu-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-flow-api-openapi.yml
- filename: skavio-eu-invoices-api-openapi.yml
  format: yaml
  label: skavio-eu Invoices API
  slug: skavio-eu-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-invoices-api-openapi.yml
- filename: skavio-eu-me-api-openapi.yml
  format: yaml
  label: skavio-eu Me API
  slug: skavio-eu-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-me-api-openapi.yml
- filename: skavio-eu-operational-notifications-api-openapi.yml
  format: yaml
  label: skavio-eu Operational notifications API
  slug: skavio-eu-operational-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-operational-notifications-api-openapi.yml
- filename: skavio-eu-paid-web-data-api-openapi.yml
  format: yaml
  label: skavio-eu paid web data API
  slug: skavio-eu-paid-web-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-paid-web-data-api-openapi.yml
- filename: skavio-eu-requests-api-openapi.yml
  format: yaml
  label: skavio-eu Requests API
  slug: skavio-eu-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-requests-api-openapi.yml
- filename: skavio-eu-skavio-accounting-api-openapi.yml
  format: yaml
  label: skavio-eu Skavio Accounting API
  slug: skavio-eu-skavio-accounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-skavio-accounting-api-openapi.yml
- filename: skavio-eu-skavio-processing-api-api-openapi.yml
  format: yaml
  label: skavio-eu Skavio processing API
  slug: skavio-eu-skavio-processing-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-skavio-processing-api-api-openapi.yml
- filename: skavio-eu-usdc-payment-verification-api-openapi.yml
  format: yaml
  label: skavio-eu USDC payment verification API
  slug: skavio-eu-usdc-payment-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-usdc-payment-verification-api-openapi.yml
- filename: skavio-eu-webhooks-api-openapi.yml
  format: yaml
  label: skavio-eu Webhooks API
  slug: skavio-eu-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-webhooks-api-openapi.yml
- filename: skavio-eu-workflow-pipelines-api-openapi.yml
  format: yaml
  label: skavio-eu Workflow pipelines API
  slug: skavio-eu-workflow-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-workflow-pipelines-api-openapi.yml
- filename: skavio-eu-x402-api-openapi.yml
  format: yaml
  label: skavio-eu X402 API
  slug: skavio-eu-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skavio-eu/openapi/skavio-eu-x402-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are prohibited from receiving them under applicable U.S. sanctions or export-control law.
  entity_types:
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  - text: You must be at least 18 years old and legally capable of entering into a contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a contract.
    value: '18'
  restricted_uses:
  - summary: Sensitive data restrictions
    text: Do not submit payment-card data, authentication secrets, classified information, regulated health data, biometric templates or other specially regulated data unless the applicable service and a written agreement expressly support it.
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
name: skavio-eu
provenance_date: '2026-11-10'
provider_name: skavio-eu
provider_slug: skavio-eu
slug: skavio-eu-eligibility
source_date: '2026-11-10'
source_filename: skavio-eu-eligibility.yml
source_heading: Eligibility
source_page: https://getskavio.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: skavio-eu\naid: skavio-eu\nurl: https://getskavio.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are prohibited from receiving them under applicable U.S. sanctions or\n    export-control law.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization.\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into a contract.\nrestricted_uses:\n- summary: Sensitive data restrictions\n  text: Do\
  \ not submit payment-card data, authentication secrets, classified information, regulated health data,\n    biometric templates or other specially regulated data unless the applicable service and a written agreement\n    expressly support it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a contract.\n"
source_yaml_url: https://artifacts.apis.io/skavio-eu/eligibility/skavio-eu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from skavio-eu's own page on 2026-11-10.
synthetic: false
tags:
- BusinessTools
- Document Processing
- Invoice Automation
- Audio Transcription
- Payments
---
