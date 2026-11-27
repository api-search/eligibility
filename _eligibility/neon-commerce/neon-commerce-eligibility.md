---
api_specs:
- filename: neon-commerce-account-api-openapi.yml
  format: yaml
  label: Neon Commerce Account API
  slug: neon-commerce-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-account-api-openapi.yml
- filename: neon-commerce-assets-api-openapi.yml
  format: yaml
  label: Neon Commerce Assets API
  slug: neon-commerce-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-assets-api-openapi.yml
- filename: neon-commerce-auth-api-openapi.yml
  format: yaml
  label: Neon Commerce Auth API
  slug: neon-commerce-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-auth-api-openapi.yml
- filename: neon-commerce-checkout-api-openapi.yml
  format: yaml
  label: Neon Commerce Checkout API
  slug: neon-commerce-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-checkout-api-openapi.yml
- filename: neon-commerce-client-api-openapi.yml
  format: yaml
  label: Neon Commerce Client API
  slug: neon-commerce-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-client-api-openapi.yml
- filename: neon-commerce-payouts-api-openapi.yml
  format: yaml
  label: Neon Commerce Payouts API
  slug: neon-commerce-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-payouts-api-openapi.yml
- filename: neon-commerce-prices-api-openapi.yml
  format: yaml
  label: Neon Commerce Prices API
  slug: neon-commerce-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-prices-api-openapi.yml
- filename: neon-commerce-pricing-sheet-api-openapi.yml
  format: yaml
  label: Neon Commerce Pricing Sheet API
  slug: neon-commerce-pricing-sheet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-pricing-sheet-api-openapi.yml
- filename: neon-commerce-purchases-api-openapi.yml
  format: yaml
  label: Neon Commerce Purchases API
  slug: neon-commerce-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-purchases-api-openapi.yml
- filename: neon-commerce-reports-api-openapi.yml
  format: yaml
  label: Neon Commerce Reports API
  slug: neon-commerce-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-reports-api-openapi.yml
- filename: neon-commerce-status-api-openapi.yml
  format: yaml
  label: Neon Commerce Status API
  slug: neon-commerce-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-status-api-openapi.yml
- filename: neon-commerce-storefront-api-openapi.yml
  format: yaml
  label: Neon Commerce Storefront API
  slug: neon-commerce-storefront-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-storefront-api-openapi.yml
- filename: neon-commerce-subscriptions-api-openapi.yml
  format: yaml
  label: Neon Commerce Subscriptions API
  slug: neon-commerce-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon-commerce/openapi/neon-commerce-subscriptions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Neon from its facilities in the United States of America. Neon makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: if applicable, on behalf of any company, organization or other legal entity on whose behalf you use the Services
    type: business
  minimum_age:
    text: YOU MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE SERVICES.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Neon reserves the right to request and verify your age as part of our compliance with regional regulations and legal restrictions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Neon Commerce
provenance_date: '2026-11-10'
provider_name: Neon Commerce
provider_slug: neon-commerce
slug: neon-commerce-eligibility
source_date: '2026-11-10'
source_filename: neon-commerce-eligibility.yml
source_heading: Eligibility
source_page: https://www.neonpay.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Neon Commerce\naid: neon-commerce\nurl: https://www.neonpay.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Neon from its facilities in the United States of America. Neon\n    makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: if applicable, on behalf of any company, organization or other legal entity on whose behalf you use the\n    Services\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ Neon reserves the right to request and verify your age as part of our compliance with regional regulations\n    and legal restrictions.\nminimum_age:\n  value: '13'\n  text: YOU MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/neon-commerce/eligibility/neon-commerce-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Neon Commerce's own page on 2026-11-10.
synthetic: false
tags:
- Commerce
- Payments
- Gaming
- Checkout
- Storefront
- Direct to Consumer
- Subscription
- Merchant of Record
- Game Monetization
- Company
---
