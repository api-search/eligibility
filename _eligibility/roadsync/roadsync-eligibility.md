---
api_specs:
- filename: roadsync-authenticated-api-openapi.yml
  format: yaml
  label: Roadsync Authenticated API
  slug: roadsync-authenticated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-authenticated-api-openapi.yml
- filename: roadsync-brokers-api-openapi.yml
  format: yaml
  label: Roadsync Brokers API
  slug: roadsync-brokers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-brokers-api-openapi.yml
- filename: roadsync-department-api-openapi.yml
  format: yaml
  label: Roadsync Department API
  slug: roadsync-department-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-department-api-openapi.yml
- filename: roadsync-directory-api-openapi.yml
  format: yaml
  label: Roadsync Directory API
  slug: roadsync-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-directory-api-openapi.yml
- filename: roadsync-eta-api-openapi.yml
  format: yaml
  label: Roadsync Eta API
  slug: roadsync-eta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-eta-api-openapi.yml
- filename: roadsync-funding-sources-api-openapi.yml
  format: yaml
  label: Roadsync funding sources API
  slug: roadsync-funding-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-funding-sources-api-openapi.yml
- filename: roadsync-invoice-api-openapi.yml
  format: yaml
  label: Roadsync Invoice API
  slug: roadsync-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-invoice-api-openapi.yml
- filename: roadsync-loads-api-openapi.yml
  format: yaml
  label: Roadsync Loads API
  slug: roadsync-loads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-loads-api-openapi.yml
- filename: roadsync-location-api-openapi.yml
  format: yaml
  label: Roadsync Location API
  slug: roadsync-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-location-api-openapi.yml
- filename: roadsync-payables-api-openapi.yml
  format: yaml
  label: Roadsync Payables API
  slug: roadsync-payables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-payables-api-openapi.yml
- filename: roadsync-payees-api-openapi.yml
  format: yaml
  label: Roadsync Payees API
  slug: roadsync-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-payees-api-openapi.yml
- filename: roadsync-payment-api-openapi.yml
  format: yaml
  label: Roadsync Payment API
  slug: roadsync-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-payment-api-openapi.yml
- filename: roadsync-ping-api-openapi.yml
  format: yaml
  label: Roadsync Ping API
  slug: roadsync-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-ping-api-openapi.yml
- filename: roadsync-product-api-openapi.yml
  format: yaml
  label: Roadsync Product API
  slug: roadsync-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-product-api-openapi.yml
- filename: roadsync-shift-api-openapi.yml
  format: yaml
  label: Roadsync Shift API
  slug: roadsync-shift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-shift-api-openapi.yml
- filename: roadsync-transactions-api-openapi.yml
  format: yaml
  label: Roadsync Transactions API
  slug: roadsync-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-transactions-api-openapi.yml
- filename: roadsync-unauthenticated-api-openapi.yml
  format: yaml
  label: Roadsync Unauthenticated API
  slug: roadsync-unauthenticated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-unauthenticated-api-openapi.yml
- filename: roadsync-work-orders-api-openapi.yml
  format: yaml
  label: Roadsync Work Orders API
  slug: roadsync-work-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roadsync/openapi/roadsync-work-orders-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our Site is intended for use only by persons who are 18 years old or older.
    value: '18'
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
name: Roadsync
provenance_date: '2026-11-10'
provider_name: Roadsync
provider_slug: roadsync
slug: roadsync-eligibility
source_date: '2026-11-10'
source_filename: roadsync-eligibility.yml
source_heading: Eligibility
source_page: https://roadsync.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roadsync\naid: roadsync\nurl: https://roadsync.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Site is intended for use only by persons who are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/roadsync/eligibility/roadsync-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Roadsync's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Payments
- Logistics
- Trucking
- Invoicing
- Transportation
- Fintech
---
