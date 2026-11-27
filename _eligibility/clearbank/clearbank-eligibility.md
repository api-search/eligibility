---
api_specs:
- filename: clearbank-accounts-api-openapi.yml
  format: yaml
  label: ClearBank Accounts API
  slug: clearbank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-accounts-api-openapi.yml
- filename: clearbank-createfxquoteendpoint-api-openapi.yml
  format: yaml
  label: ClearBank Create Fx Quote Endpoint API
  slug: clearbank-createfxquoteendpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-createfxquoteendpoint-api-openapi.yml
- filename: clearbank-customer-api-openapi.yml
  format: yaml
  label: ClearBank Customer API
  slug: clearbank-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-customer-api-openapi.yml
- filename: clearbank-customer-due-diligence-api-openapi.yml
  format: yaml
  label: ClearBank Customer Due Diligence API
  slug: clearbank-customer-due-diligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-customer-due-diligence-api-openapi.yml
- filename: clearbank-externalcrossbordercustomerpaymentsv4-api-openapi.yml
  format: yaml
  label: ClearBank External Cross Border Customer Payments V4 API
  slug: clearbank-externalcrossbordercustomerpaymentsv4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-externalcrossbordercustomerpaymentsv4-api-openapi.yml
- filename: clearbank-externalcustomerpaymentsv6-api-openapi.yml
  format: yaml
  label: ClearBank External Customer Payments V6 API
  slug: clearbank-externalcustomerpaymentsv6-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-externalcustomerpaymentsv6-api-openapi.yml
- filename: clearbank-externalinstitutionpaymentsv6-api-openapi.yml
  format: yaml
  label: ClearBank External Institution Payments V6 API
  slug: clearbank-externalinstitutionpaymentsv6-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-externalinstitutionpaymentsv6-api-openapi.yml
- filename: clearbank-externalreturnpaymentsv6-api-openapi.yml
  format: yaml
  label: ClearBank External Return Payments V6 API
  slug: clearbank-externalreturnpaymentsv6-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-externalreturnpaymentsv6-api-openapi.yml
- filename: clearbank-fpspayments-api-openapi.yml
  format: yaml
  label: ClearBank Fps Payments API
  slug: clearbank-fpspayments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-fpspayments-api-openapi.yml
- filename: clearbank-fx-orders-api-openapi.yml
  format: yaml
  label: ClearBank Fx Orders API
  slug: clearbank-fx-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-fx-orders-api-openapi.yml
- filename: clearbank-payments-api-openapi.yml
  format: yaml
  label: ClearBank Payments API
  slug: clearbank-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-payments-api-openapi.yml
- filename: clearbank-retail-api-openapi.yml
  format: yaml
  label: ClearBank Retail API
  slug: clearbank-retail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-retail-api-openapi.yml
- filename: clearbank-sct-payments-api-openapi.yml
  format: yaml
  label: ClearBank SCT Payments API
  slug: clearbank-sct-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-sct-payments-api-openapi.yml
- filename: clearbank-secondaryreferencedata-api-openapi.yml
  format: yaml
  label: ClearBank Secondary Reference Data API
  slug: clearbank-secondaryreferencedata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-secondaryreferencedata-api-openapi.yml
- filename: clearbank-co-p-api-openapi.yml
  format: yaml
  label: ClearBank Co P API
  slug: clearbank-co-p-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearbank/openapi/clearbank-co-p-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, please note that these Website Terms, their subject matter and their formation, are governed by English law.
    type: individual
  - text: If you are a business, these Website Terms, their subject matter and their formation (and any non-contractual disputes or claims) are governed by English law.
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
name: ClearBank
provenance_date: '2026-11-09'
provider_name: ClearBank
provider_slug: clearbank
slug: clearbank-eligibility
source_date: '2026-11-09'
source_filename: clearbank-eligibility.yml
source_heading: Eligibility
source_page: https://clear.bank/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClearBank\naid: clearbank\nurl: https://clear.bank/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, please note that these Website Terms, their subject matter and their formation, are\n    governed by English law.\n- type: business\n  text: If you are a business, these Website Terms, their subject matter and their formation (and any non-contractual\n    disputes or claims) are governed by English law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearbank/eligibility/clearbank-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from ClearBank's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Banking as a Service
- Embedded Banking
- Payments
- Clearing
- Faster Payments
- CHAPS
- Multi-Currency
- Foreign Exchange
- Open Banking
- United Kingdom
- Fintech
---
