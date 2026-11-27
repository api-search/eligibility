---
api_specs:
- filename: bolt-financial-account-api-openapi.yml
  format: yaml
  label: Bolt Financial Account API
  slug: bolt-financial-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-account-api-openapi.yml
- filename: bolt-financial-callbacks-api-openapi.yml
  format: yaml
  label: Bolt Financial Callbacks API
  slug: bolt-financial-callbacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-callbacks-api-openapi.yml
- filename: bolt-financial-configuration-api-openapi.yml
  format: yaml
  label: Bolt Financial Configuration API
  slug: bolt-financial-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-configuration-api-openapi.yml
- filename: bolt-financial-orders-api-openapi.yml
  format: yaml
  label: Bolt Financial Orders API
  slug: bolt-financial-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-orders-api-openapi.yml
- filename: bolt-financial-payments-api-openapi.yml
  format: yaml
  label: Bolt Financial Payments API
  slug: bolt-financial-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-payments-api-openapi.yml
- filename: bolt-financial-statements-api-openapi.yml
  format: yaml
  label: Bolt Financial Statements API
  slug: bolt-financial-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-statements-api-openapi.yml
- filename: bolt-financial-subscriptions-api-openapi.yml
  format: yaml
  label: Bolt Financial Subscriptions API
  slug: bolt-financial-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-subscriptions-api-openapi.yml
- filename: bolt-financial-testing-api-openapi.yml
  format: yaml
  label: Bolt Financial Testing API
  slug: bolt-financial-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-testing-api-openapi.yml
- filename: bolt-financial-tokenizer-api-openapi.yml
  format: yaml
  label: Bolt Financial Tokenizer API
  slug: bolt-financial-tokenizer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-tokenizer-api-openapi.yml
- filename: bolt-financial-transactions-api-openapi.yml
  format: yaml
  label: Bolt Financial Transactions API
  slug: bolt-financial-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-transactions-api-openapi.yml
- filename: bolt-financial-webhooks-api-openapi.yml
  format: yaml
  label: Bolt Financial Webhooks API
  slug: bolt-financial-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-webhooks-api-openapi.yml
- filename: bolt-financial-oauth-api-openapi.yml
  format: yaml
  label: Bolt Financial O Auth API
  slug: bolt-financial-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all features are available to all persons or in all geographic locations, or appropriate for use outside the United States.
  minimum_age:
    text: YOU MUST BE AT LEAST AGE 18 TO ACCESS AND USE THE SERVICES.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to use the Services, Bolt may need to confirm your identity and screen transactions to prevent fraud when you make a purchase.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bolt Financial
provenance_date: '2026-11-09'
provider_name: Bolt Financial
provider_slug: bolt-financial
slug: bolt-financial-eligibility
source_date: '2026-11-09'
source_filename: bolt-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.boltapp.com/end-user-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bolt Financial\naid: bolt-financial\nurl: https://www.boltapp.com/end-user-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all features are available to all persons or in all geographic locations, or appropriate for use outside\n    the United States.\nentity_types: []\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of\n    or for the benefit of any third party\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order\
  \ to use the Services, Bolt may need to confirm your identity and screen transactions to prevent\n    fraud when you make a purchase.\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST AGE 18 TO ACCESS AND USE THE SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/bolt-financial/eligibility/bolt-financial-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bolt Financial's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Checkout
- E-Commerce
- Fintech
- Subscription
- Tokenization
- Fraud Prevention
- Identity
- Webhook
---
