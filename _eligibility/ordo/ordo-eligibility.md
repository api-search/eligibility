---
api_specs:
- filename: ordo-account-data-client-hosted-api-openapi.yml
  format: yaml
  label: Ordo Account Data - Client Hosted API
  slug: ordo-account-data-client-hosted-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordo/openapi/ordo-account-data-client-hosted-api-openapi.yml
- filename: ordo-account-verification-client-hosted-api-openapi.yml
  format: yaml
  label: Ordo Account Verification - Client Hosted API
  slug: ordo-account-verification-client-hosted-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordo/openapi/ordo-account-verification-client-hosted-api-openapi.yml
- filename: ordo-bank-accounts-api-openapi.yml
  format: yaml
  label: Ordo Bank accounts API
  slug: ordo-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordo/openapi/ordo-bank-accounts-api-openapi.yml
- filename: ordo-client-hosted-api-openapi.yml
  format: yaml
  label: Ordo Client hosted API
  slug: ordo-client-hosted-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordo/openapi/ordo-client-hosted-api-openapi.yml
- filename: ordo-create-a-mandate-api-openapi.yml
  format: yaml
  label: Ordo Create a mandate API
  slug: ordo-create-a-mandate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordo/openapi/ordo-create-a-mandate-api-openapi.yml
- filename: ordo-ordo-hosted-api-openapi.yml
  format: yaml
  label: Ordo Hosted API
  slug: ordo-ordo-hosted-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordo/openapi/ordo-ordo-hosted-api-openapi.yml
- filename: ordo-retrieve-mandate-details-api-openapi.yml
  format: yaml
  label: Ordo Retrieve mandate details API
  slug: ordo-retrieve-mandate-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordo/openapi/ordo-retrieve-mandate-details-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Enable direct bank payments in your app or website via our open banking API - for licensed AIS/PIS providers.
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
name: Ordo
provenance_date: '2026-11-10'
provider_name: Ordo
provider_slug: ordo
slug: ordo-eligibility
source_date: '2026-11-10'
source_filename: ordo-eligibility.yml
source_heading: Eligibility
source_page: https://ordopay.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ordo\naid: ordo\nurl: https://ordopay.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Enable direct bank payments in your app or website via our open banking API - for licensed AIS/PIS providers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ordo/eligibility/ordo-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Ordo's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Open Banking
- Account-to-Account
- Payment Initiation
- Variable Recurring Payments
- Request to Pay
- Real-Time Payments
- Faster Payments
- PSD2
- Account Information
- Defunct
---
