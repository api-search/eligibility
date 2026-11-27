---
api_specs:
- filename: subotiz-com-checkout-session-api-openapi.yml
  format: yaml
  label: subotiz-com Checkout Session API
  slug: subotiz-com-checkout-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-checkout-session-api-openapi.yml
- filename: subotiz-com-customer-api-openapi.yml
  format: yaml
  label: subotiz-com Customer API
  slug: subotiz-com-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-customer-api-openapi.yml
- filename: subotiz-com-customer-portal-api-openapi.yml
  format: yaml
  label: subotiz-com Customer Portal API
  slug: subotiz-com-customer-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-customer-portal-api-openapi.yml
- filename: subotiz-com-default-api-openapi.yml
  format: yaml
  label: subotiz-com 争议 API
  slug: subotiz-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-default-api-openapi.yml
- filename: subotiz-com-discount-api-openapi.yml
  format: yaml
  label: subotiz-com Discount API
  slug: subotiz-com-discount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-discount-api-openapi.yml
- filename: subotiz-com-invoice-api-openapi.yml
  format: yaml
  label: subotiz-com Invoice API
  slug: subotiz-com-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-invoice-api-openapi.yml
- filename: subotiz-com-payment-api-openapi.yml
  format: yaml
  label: subotiz-com Payment API
  slug: subotiz-com-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-payment-api-openapi.yml
- filename: subotiz-com-price-api-openapi.yml
  format: yaml
  label: subotiz-com Price API
  slug: subotiz-com-price-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-price-api-openapi.yml
- filename: subotiz-com-product-api-openapi.yml
  format: yaml
  label: subotiz-com Product API
  slug: subotiz-com-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-product-api-openapi.yml
- filename: subotiz-com-refund-api-openapi.yml
  format: yaml
  label: subotiz-com Refund API
  slug: subotiz-com-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-refund-api-openapi.yml
- filename: subotiz-com-subscription-api-openapi.yml
  format: yaml
  label: subotiz-com Subscription API
  slug: subotiz-com-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-subscription-api-openapi.yml
- filename: subotiz-com-trade-api-openapi.yml
  format: yaml
  label: subotiz-com Trade API
  slug: subotiz-com-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-trade-api-openapi.yml
- filename: subotiz-com-webhook-api-openapi.yml
  format: yaml
  label: subotiz-com Webhook API
  slug: subotiz-com-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subotiz-com/openapi/subotiz-com-webhook-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all Services and features are available in every jurisdiction and we are under no obligation to make any Services or features available in any jurisdiction
  minimum_age:
    text: you represent that (1) you are age 18 or older
    value: '18'
  restricted_uses:
  - summary: Prohibited content and activities
    text: use the Services to knowingly post, transmit, upload, link to, send or store any content that is prohibited or restricted in the AUP
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may reject your application for an Account, or cancel an existing Account, for any reason, at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: subotiz-com
provenance_date: '2026-11-10'
provider_name: subotiz-com
provider_slug: subotiz-com
slug: subotiz-com-eligibility
source_date: '2026-11-10'
source_filename: subotiz-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.subotiz.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: subotiz-com\naid: subotiz-com\nurl: https://www.subotiz.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Not all Services and features are available in every jurisdiction and we are under no obligation to make\n    any Services or features available in any jurisdiction\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content and activities\n  text: use the Services to knowingly post, transmit, upload, link to, send or store any content that is prohibited\n    or restricted in the AUP\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: We may reject your application for an Account, or cancel an existing Account, for any reason, at our sole\n    discretion.\nminimum_age:\n  value: '18'\n  text: you represent that (1) you are age 18 or older\n"
source_yaml_url: https://artifacts.apis.io/subotiz-com/eligibility/subotiz-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from subotiz-com's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Artificial Intelligence
- Billing
- Software-as-a-Service
- Fintech
- Company
---
