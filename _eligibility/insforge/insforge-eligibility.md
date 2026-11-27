---
api_specs:
- filename: insforge-admin-api-openapi.yml
  format: yaml
  label: Insforge Admin API
  slug: insforge-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-admin-api-openapi.yml
- filename: insforge-channels-api-openapi.yml
  format: yaml
  label: Insforge Channels API
  slug: insforge-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-channels-api-openapi.yml
- filename: insforge-client-api-openapi.yml
  format: yaml
  label: Insforge Client API
  slug: insforge-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-client-api-openapi.yml
- filename: insforge-configuration-api-openapi.yml
  format: yaml
  label: Insforge Configuration API
  slug: insforge-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-configuration-api-openapi.yml
- filename: insforge-messages-api-openapi.yml
  format: yaml
  label: Insforge Messages API
  slug: insforge-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-messages-api-openapi.yml
- filename: insforge-payment-webhooks-api-openapi.yml
  format: yaml
  label: Insforge Payment Webhooks API
  slug: insforge-payment-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-payment-webhooks-api-openapi.yml
- filename: insforge-permissions-api-openapi.yml
  format: yaml
  label: Insforge Permissions API
  slug: insforge-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-permissions-api-openapi.yml
- filename: insforge-razorpay-payments-api-openapi.yml
  format: yaml
  label: Insforge Razorpay Payments API
  slug: insforge-razorpay-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-razorpay-payments-api-openapi.yml
- filename: insforge-s3-access-keys-api-openapi.yml
  format: yaml
  label: Insforge S3 Access Keys API
  slug: insforge-s3-access-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-s3-access-keys-api-openapi.yml
- filename: insforge-s3-protocol-api-openapi.yml
  format: yaml
  label: Insforge S3 Protocol API
  slug: insforge-s3-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-s3-protocol-api-openapi.yml
- filename: insforge-stripe-payments-api-openapi.yml
  format: yaml
  label: Insforge Stripe Payments API
  slug: insforge-stripe-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-stripe-payments-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF ENTERING INTO THIS AGREEMENT FOR AN ORGANIZATION, THAT YOU HAVE THE LEGAL AUTHORITY TO BIND THAT ORGANIZATION
    type: business
  minimum_age:
    text: null
    value: null
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
name: Insforge
provenance_date: '2026-11-09'
provider_name: Insforge
provider_slug: insforge
slug: insforge-eligibility
source_date: '2026-11-09'
source_filename: insforge-eligibility.yml
source_heading: Eligibility
source_page: https://insforge.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Insforge\naid: insforge\nurl: https://insforge.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF ENTERING INTO THIS AGREEMENT FOR AN ORGANIZATION, THAT YOU HAVE THE LEGAL AUTHORITY TO BIND THAT ORGANIZATION\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/insforge/eligibility/insforge-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Insforge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Backend-as-a-Service
- Agent-Native
- Cloud Infrastructure
- Database
- Authentication
- Storage
- Serverless
- Edge Functions
- AI Gateway
- Payments
- Real-Time
- Open Source
- Y Combinator
---
