---
api_specs:
- filename: zerosettle-cancel-flow-api-openapi.yml
  format: yaml
  label: ZeroSettle Cancel Flow API
  slug: zerosettle-cancel-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-cancel-flow-api-openapi.yml
- filename: zerosettle-checkout-api-openapi.yml
  format: yaml
  label: ZeroSettle Checkout API
  slug: zerosettle-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-checkout-api-openapi.yml
- filename: zerosettle-entitlements-api-openapi.yml
  format: yaml
  label: ZeroSettle Entitlements API
  slug: zerosettle-entitlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-entitlements-api-openapi.yml
- filename: zerosettle-events-api-openapi.yml
  format: yaml
  label: ZeroSettle Events API
  slug: zerosettle-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-events-api-openapi.yml
- filename: zerosettle-migration-api-openapi.yml
  format: yaml
  label: ZeroSettle Migration API
  slug: zerosettle-migration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-migration-api-openapi.yml
- filename: zerosettle-products-api-openapi.yml
  format: yaml
  label: ZeroSettle Products API
  slug: zerosettle-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-products-api-openapi.yml
- filename: zerosettle-restore-api-openapi.yml
  format: yaml
  label: ZeroSettle Restore API
  slug: zerosettle-restore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-restore-api-openapi.yml
- filename: zerosettle-storekit-api-openapi.yml
  format: yaml
  label: ZeroSettle StoreKit API
  slug: zerosettle-storekit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-storekit-api-openapi.yml
- filename: zerosettle-subscriptions-api-openapi.yml
  format: yaml
  label: ZeroSettle Subscriptions API
  slug: zerosettle-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-subscriptions-api-openapi.yml
- filename: zerosettle-transactions-api-openapi.yml
  format: yaml
  label: ZeroSettle Transactions API
  slug: zerosettle-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-transactions-api-openapi.yml
- filename: zerosettle-upgrade-offers-api-openapi.yml
  format: yaml
  label: ZeroSettle Upgrade Offers API
  slug: zerosettle-upgrade-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-upgrade-offers-api-openapi.yml
- filename: zerosettle-user-offer-api-openapi.yml
  format: yaml
  label: ZeroSettle User Offer API
  slug: zerosettle-user-offer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerosettle/openapi/zerosettle-user-offer-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of a business or other legal entity, you represent and warrant that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: To use the Services, you must be at least eighteen (18) years of age and have the legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent transactions
    text: use the Services to submit, process, or facilitate transactions that are illegal, fraudulent, or prohibited under applicable law or these Terms
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
name: ZeroSettle
provenance_date: '2026-11-10'
provider_name: ZeroSettle
provider_slug: zerosettle
slug: zerosettle-eligibility
source_date: '2026-11-10'
source_filename: zerosettle-eligibility.yml
source_heading: Eligibility
source_page: https://zerosettle.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZeroSettle\naid: zerosettle\nurl: https://zerosettle.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a business or other legal entity, you represent and warrant that\n    you have authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Illegal or fraudulent transactions\n  text: use the Services to submit, process, or facilitate transactions that are illegal, fraudulent, or prohibited\n    under applicable law or these Terms\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Services, you must be at least eighteen (18) years of age and have the legal capacity to enter\n    into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/zerosettle/eligibility/zerosettle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ZeroSettle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- In-App Purchase
- Subscription
- Merchant of Record
- Billing
- Mobile
- Developer Tools
---
