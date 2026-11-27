---
api_specs:
- filename: wells-fargo-ach-payments-api-openapi.yml
  format: yaml
  label: Wells Fargo ACH Payments API
  slug: ach-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wells-fargo/openapi/wells-fargo-ach-payments-api-openapi.yml
- filename: wells-fargo-accounts-api-openapi.yml
  format: yaml
  label: wells-fargo Accounts API
  slug: wells-fargo-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wells-fargo/openapi/wells-fargo-accounts-api-openapi.yml
- filename: wells-fargo-payment-batches-api-openapi.yml
  format: yaml
  label: wells-fargo Payment Batches API
  slug: wells-fargo-payment-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wells-fargo/openapi/wells-fargo-payment-batches-api-openapi.yml
- filename: wells-fargo-payment-returns-api-openapi.yml
  format: yaml
  label: wells-fargo Payment Returns API
  slug: wells-fargo-payment-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wells-fargo/openapi/wells-fargo-payment-returns-api-openapi.yml
- filename: wells-fargo-payments-api-openapi.yml
  format: yaml
  label: wells-fargo Payments API
  slug: wells-fargo-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wells-fargo/openapi/wells-fargo-payments-api-openapi.yml
- filename: wells-fargo-transactions-api-openapi.yml
  format: yaml
  label: wells-fargo Transactions API
  slug: wells-fargo-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wells-fargo/openapi/wells-fargo-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” and “your” refer to any person who accesses or uses the Site or Services.
    type: individual
  minimum_age:
    text: If you are under the age of 13 years old and are invited to use the Chat service, you must not use the Chat service and you must leave the Site.
    value: '13'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Services, including the Site, only for lawful purposes
  - summary: Chat service age limit
    text: If you are under the age of 13 years old and are invited to use the Chat service, you must not use the Chat service
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
name: Wells Fargo
provenance_date: '2026-11-10'
provider_name: Wells Fargo
provider_slug: wells-fargo
slug: wells-fargo-eligibility
source_date: '2026-11-10'
source_filename: wells-fargo-eligibility.yml
source_heading: Eligibility
source_page: https://www.wellsfargo.com/privacy-security/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wells Fargo\naid: wells-fargo\nurl: https://www.wellsfargo.com/privacy-security/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” and “your” refer to any person who accesses or uses the Site or Services.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Services, including the Site, only for lawful purposes\n- summary: Chat service age limit\n  text: If you are under the age of 13 years old and are invited to use the Chat service, you must not use the Chat\n    service\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under the age of 13 years old and are invited to use the Chat service, you must not use the Chat\n    service and you must leave the Site.\n"
source_yaml_url: https://artifacts.apis.io/wells-fargo/eligibility/wells-fargo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Wells Fargo's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 100
- Banking
- Consumer Banking
---
