---
api_specs:
- filename: klarna-push-notifications-asyncapi.yml
  format: yaml
  label: Klarna Push Notifications
  slug: klarna-push-notifications
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/klarna/asyncapi/klarna-push-notifications-asyncapi.yml
- filename: klarna-captures-api-openapi.yml
  format: yaml
  label: Klarna Captures API
  slug: klarna-captures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-captures-api-openapi.yml
- filename: klarna-checkout-api-openapi.yml
  format: yaml
  label: Klarna Checkout API
  slug: klarna-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-checkout-api-openapi.yml
- filename: klarna-customer-token-api-openapi.yml
  format: yaml
  label: Klarna Customer Token API
  slug: klarna-customer-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-customer-token-api-openapi.yml
- filename: klarna-hpp-api-openapi.yml
  format: yaml
  label: Klarna Hpp API
  slug: klarna-hpp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-hpp-api-openapi.yml
- filename: klarna-merchant-urls-address-update-api-openapi.yml
  format: yaml
  label: Klarna Merchant Urls.address Update API
  slug: klarna-merchant-urls-address-update-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-merchant-urls-address-update-api-openapi.yml
- filename: klarna-merchant-urls-country-change-api-openapi.yml
  format: yaml
  label: Klarna Merchant Urls.country Change API
  slug: klarna-merchant-urls-country-change-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-merchant-urls-country-change-api-openapi.yml
- filename: klarna-merchant-urls-shipping-option-update-api-openapi.yml
  format: yaml
  label: Klarna Merchant Urls.shipping Option Update API
  slug: klarna-merchant-urls-shipping-option-update-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-merchant-urls-shipping-option-update-api-openapi.yml
- filename: klarna-merchant-urls-validation-api-openapi.yml
  format: yaml
  label: Klarna Merchant Urls.validation API
  slug: klarna-merchant-urls-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-merchant-urls-validation-api-openapi.yml
- filename: klarna-orders-api-openapi.yml
  format: yaml
  label: Klarna Orders API
  slug: klarna-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-orders-api-openapi.yml
- filename: klarna-payments-api-openapi.yml
  format: yaml
  label: Klarna Payments API
  slug: klarna-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-payments-api-openapi.yml
- filename: klarna-payouts-api-openapi.yml
  format: yaml
  label: Klarna Payouts API
  slug: klarna-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-payouts-api-openapi.yml
- filename: klarna-refunds-api-openapi.yml
  format: yaml
  label: Klarna Refunds API
  slug: klarna-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-refunds-api-openapi.yml
- filename: klarna-reports-api-openapi.yml
  format: yaml
  label: Klarna Reports API
  slug: klarna-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-reports-api-openapi.yml
- filename: klarna-transactions-api-openapi.yml
  format: yaml
  label: Klarna Transactions API
  slug: klarna-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-transactions-api-openapi.yml
- filename: klarna-merchant-card-api-openapi.yml
  format: yaml
  label: Klarna Merchant Card API
  slug: klarna-merchant-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klarna/openapi/klarna-merchant-card-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: You agree to not upload, publish or share any content which we may determine, in our sole discretion, (i) is unlawful, fraudulent, abusive or threatening
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
name: Klarna
provenance_date: '2026-11-09'
provider_name: Klarna
provider_slug: klarna
slug: klarna-eligibility
source_date: '2026-11-09'
source_filename: klarna-eligibility.yml
source_heading: Eligibility
source_page: https://www.klarna.com/us/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klarna\naid: klarna\nurl: https://www.klarna.com/us/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: You agree to not upload, publish or share any content which we may determine, in our sole discretion, (i)\n    is unlawful, fraudulent, abusive or threatening\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/klarna/eligibility/klarna-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Klarna's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Buy Now Pay Later
- Payments
- Cards
- Shopping
- Banking
- Checkout
- Order Management
- Settlement
- Open Banking
- PSD2
- Consumer Credit
- Sweden
- Agentic Commerce
- Consumer Finance
---
