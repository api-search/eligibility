---
api_specs:
- filename: imprint-customer-links-api-openapi.yml
  format: yaml
  label: Imprint Customer Links API
  slug: imprint-customer-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-customer-links-api-openapi.yml
- filename: imprint-customer-sessions-api-openapi.yml
  format: yaml
  label: Imprint Customer Sessions API
  slug: imprint-customer-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-customer-sessions-api-openapi.yml
- filename: imprint-customers-api-openapi.yml
  format: yaml
  label: Imprint Customers API
  slug: imprint-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-customers-api-openapi.yml
- filename: imprint-keys-api-openapi.yml
  format: yaml
  label: Imprint Keys API
  slug: imprint-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-keys-api-openapi.yml
- filename: imprint-offers-api-openapi.yml
  format: yaml
  label: Imprint Offers API
  slug: imprint-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-offers-api-openapi.yml
- filename: imprint-order-events-api-openapi.yml
  format: yaml
  label: Imprint Order Events API
  slug: imprint-order-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-order-events-api-openapi.yml
- filename: imprint-orders-api-openapi.yml
  format: yaml
  label: Imprint Orders API
  slug: imprint-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-orders-api-openapi.yml
- filename: imprint-payment-methods-api-openapi.yml
  format: yaml
  label: Imprint Payment Methods API
  slug: imprint-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-payment-methods-api-openapi.yml
- filename: imprint-rewards-api-openapi.yml
  format: yaml
  label: Imprint Rewards API
  slug: imprint-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-rewards-api-openapi.yml
- filename: imprint-simulate-reward-api-openapi.yml
  format: yaml
  label: Imprint Simulate Reward API
  slug: imprint-simulate-reward-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-simulate-reward-api-openapi.yml
- filename: imprint-simulate-statement-reward-api-openapi.yml
  format: yaml
  label: Imprint Simulate Statement Reward API
  slug: imprint-simulate-statement-reward-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-simulate-statement-reward-api-openapi.yml
- filename: imprint-simulate-transaction-event-api-openapi.yml
  format: yaml
  label: Imprint Simulate Transaction Event API
  slug: imprint-simulate-transaction-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-simulate-transaction-event-api-openapi.yml
- filename: imprint-transaction-intents-api-openapi.yml
  format: yaml
  label: Imprint Transaction Intents API
  slug: imprint-transaction-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-transaction-intents-api-openapi.yml
- filename: imprint-transactions-api-openapi.yml
  format: yaml
  label: Imprint Transactions API
  slug: imprint-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-transactions-api-openapi.yml
- filename: imprint-webhooks-api-openapi.yml
  format: yaml
  label: Imprint Webhooks API
  slug: imprint-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-webhooks-api-openapi.yml
- filename: imprint-applications-api-openapi.yml
  format: yaml
  label: Imprint Applications API
  slug: imprint-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-applications-api-openapi.yml
- filename: imprint-card-designs-api-openapi.yml
  format: yaml
  label: Imprint Card Designs API
  slug: imprint-card-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-card-designs-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This website is not intended for use by individuals in any jurisdiction or country where such use would be contrary to applicable laws or regulations.
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
name: Imprint
provenance_date: '2026-11-09'
provider_name: Imprint
provider_slug: imprint
slug: imprint-eligibility
source_date: '2026-11-09'
source_filename: imprint-eligibility.yml
source_heading: Eligibility
source_page: https://imprint.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imprint\naid: imprint\nurl: https://imprint.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This website is not intended for use by individuals in any jurisdiction or country where such use would\n    be contrary to applicable laws or regulations.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imprint/eligibility/imprint-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Imprint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Credit Cards
- Co-Branded Cards
- Payments
- Loans
- Rewards
- Loyalty
- Embedded Finance
---
