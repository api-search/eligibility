---
api_specs:
- filename: checkoutpage-com-account-api-openapi.yml
  format: yaml
  label: Checkout Page Account API
  slug: checkoutpage-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-account-api-openapi.yml
- filename: checkoutpage-com-checkout-pages-api-openapi.yml
  format: yaml
  label: Checkout Page Checkout Pages API
  slug: checkoutpage-com-checkout-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-checkout-pages-api-openapi.yml
- filename: checkoutpage-com-coupons-api-openapi.yml
  format: yaml
  label: Checkout Page Coupons API
  slug: checkoutpage-com-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-coupons-api-openapi.yml
- filename: checkoutpage-com-customers-api-openapi.yml
  format: yaml
  label: Checkout Page Customers API
  slug: checkoutpage-com-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-customers-api-openapi.yml
- filename: checkoutpage-com-events-api-openapi.yml
  format: yaml
  label: Checkout Page Events API
  slug: checkoutpage-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-events-api-openapi.yml
- filename: checkoutpage-com-files-api-openapi.yml
  format: yaml
  label: Checkout Page Files API
  slug: checkoutpage-com-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-files-api-openapi.yml
- filename: checkoutpage-com-forms-api-openapi.yml
  format: yaml
  label: Checkout Page Forms API
  slug: checkoutpage-com-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-forms-api-openapi.yml
- filename: checkoutpage-com-invoices-api-openapi.yml
  format: yaml
  label: Checkout Page Invoices API
  slug: checkoutpage-com-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-invoices-api-openapi.yml
- filename: checkoutpage-com-payments-api-openapi.yml
  format: yaml
  label: Checkout Page Payments API
  slug: checkoutpage-com-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-payments-api-openapi.yml
- filename: checkoutpage-com-products-api-openapi.yml
  format: yaml
  label: Checkout Page Products API
  slug: checkoutpage-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-products-api-openapi.yml
- filename: checkoutpage-com-subscription-payments-api-openapi.yml
  format: yaml
  label: Checkout Page Subscription Payments API
  slug: checkoutpage-com-subscription-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-subscription-payments-api-openapi.yml
- filename: checkoutpage-com-subscriptions-api-openapi.yml
  format: yaml
  label: Checkout Page Subscriptions API
  slug: checkoutpage-com-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-subscriptions-api-openapi.yml
- filename: checkoutpage-com-tax-rates-api-openapi.yml
  format: yaml
  label: Checkout Page Tax Rates API
  slug: checkoutpage-com-tax-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-tax-rates-api-openapi.yml
- filename: checkoutpage-com-themes-api-openapi.yml
  format: yaml
  label: Checkout Page Themes API
  slug: checkoutpage-com-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-themes-api-openapi.yml
- filename: checkoutpage-com-webhooks-api-openapi.yml
  format: yaml
  label: Checkout Page Webhooks API
  slug: checkoutpage-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkoutpage-com/openapi/checkoutpage-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the service if you are a person barred from the Service under the laws of Delaware, United States or other countries, including the country in which you are resident or from which you use the Service.
  minimum_age:
    text: You may not use the service unless you are over the age of 13.
    value: '13'
  restricted_uses:
  - summary: Automated accounts prohibited
    text: Accounts created by automated methods are not permitted.
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
name: Checkout Page
provenance_date: '2026-11-09'
provider_name: Checkout Page
provider_slug: checkoutpage-com
slug: checkoutpage-com-eligibility
source_date: '2026-11-09'
source_filename: checkoutpage-com-eligibility.yml
source_heading: Eligibility
source_page: https://checkoutpage.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Checkout Page\naid: checkoutpage-com\nurl: https://checkoutpage.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the service if you are a person barred from the Service under the laws of Delaware, United\n    States or other countries, including the country in which you are resident or from which you use the Service.\nentity_types: []\nrestricted_uses:\n- summary: Automated accounts prohibited\n  text: Accounts created by automated methods are not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You may not use the service unless you are over the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/checkoutpage-com/eligibility/checkoutpage-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Checkout Page's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Checkout
- Stripe
- No-Code
- E-Commerce
- Subscription
- Event Ticketing
---
