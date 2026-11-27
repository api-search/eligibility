---
api_specs:
- filename: simplifi-simplifipay-auth-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay Auth API
  slug: simplifi-simplifipay-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-auth-api-openapi.yml
- filename: simplifi-simplifipay-card-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay Card API
  slug: simplifi-simplifipay-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-card-api-openapi.yml
- filename: simplifi-simplifipay-card-program-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay Card Program API
  slug: simplifi-simplifipay-card-program-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-card-program-api-openapi.yml
- filename: simplifi-simplifipay-fee-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay Fee API
  slug: simplifi-simplifipay-fee-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-fee-api-openapi.yml
- filename: simplifi-simplifipay-funding-source-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay Funding Source API
  slug: simplifi-simplifipay-funding-source-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-funding-source-api-openapi.yml
- filename: simplifi-simplifipay-transaction-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay Transaction API
  slug: simplifi-simplifipay-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-transaction-api-openapi.yml
- filename: simplifi-simplifipay-user-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay User API
  slug: simplifi-simplifipay-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-user-api-openapi.yml
- filename: simplifi-simplifipay-webhook-api-openapi.yml
  format: yaml
  label: Simplifi/Simplifipay Webhook API
  slug: simplifi-simplifipay-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplifi-simplifipay/openapi/simplifi-simplifipay-webhook-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
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
name: Simplifipay
provenance_date: '2026-11-10'
provider_name: Simplifipay
provider_slug: simplifi-simplifipay
slug: simplifi-simplifipay-eligibility
source_date: '2026-11-10'
source_filename: simplifi-simplifipay-eligibility.yml
source_heading: Eligibility
source_page: https://simplifipay.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simplifipay\naid: simplifi-simplifipay\nurl: https://simplifipay.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/simplifi-simplifipay/eligibility/simplifi-simplifipay-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Simplifipay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cards
- Card Issuing
- Virtual Cards
- Fintech
- Payments
- Banking as a Service
- Embedded Finance
- GCC
- Webhook
---
