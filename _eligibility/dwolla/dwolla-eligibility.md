---
api_specs:
- filename: dwolla-accounts-api-openapi.yml
  format: yaml
  label: Dwolla Accounts API
  slug: dwolla-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-accounts-api-openapi.yml
- filename: dwolla-beneficial-owners-api-openapi.yml
  format: yaml
  label: Dwolla beneficial owners API
  slug: dwolla-beneficial-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-beneficial-owners-api-openapi.yml
- filename: dwolla-client-tokens-api-openapi.yml
  format: yaml
  label: Dwolla client tokens API
  slug: dwolla-client-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-client-tokens-api-openapi.yml
- filename: dwolla-customers-api-openapi.yml
  format: yaml
  label: Dwolla Customers API
  slug: dwolla-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-customers-api-openapi.yml
- filename: dwolla-documents-api-openapi.yml
  format: yaml
  label: Dwolla Documents API
  slug: dwolla-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-documents-api-openapi.yml
- filename: dwolla-events-api-openapi.yml
  format: yaml
  label: Dwolla Events API
  slug: dwolla-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-events-api-openapi.yml
- filename: dwolla-exchange-sessions-api-openapi.yml
  format: yaml
  label: Dwolla exchange sessions API
  slug: dwolla-exchange-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-exchange-sessions-api-openapi.yml
- filename: dwolla-exchanges-api-openapi.yml
  format: yaml
  label: Dwolla Exchanges API
  slug: dwolla-exchanges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-exchanges-api-openapi.yml
- filename: dwolla-funding-sources-api-openapi.yml
  format: yaml
  label: Dwolla funding sources API
  slug: dwolla-funding-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-funding-sources-api-openapi.yml
- filename: dwolla-kba-api-openapi.yml
  format: yaml
  label: Dwolla Kba API
  slug: dwolla-kba-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-kba-api-openapi.yml
- filename: dwolla-labels-api-openapi.yml
  format: yaml
  label: Dwolla Labels API
  slug: dwolla-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-labels-api-openapi.yml
- filename: dwolla-mass-payments-api-openapi.yml
  format: yaml
  label: Dwolla mass payments API
  slug: dwolla-mass-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-mass-payments-api-openapi.yml
- filename: dwolla-root-api-openapi.yml
  format: yaml
  label: Dwolla Root API
  slug: dwolla-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-root-api-openapi.yml
- filename: dwolla-sandbox-simulations-api-openapi.yml
  format: yaml
  label: Dwolla sandbox simulations API
  slug: dwolla-sandbox-simulations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-sandbox-simulations-api-openapi.yml
- filename: dwolla-tokens-api-openapi.yml
  format: yaml
  label: Dwolla Tokens API
  slug: dwolla-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-tokens-api-openapi.yml
- filename: dwolla-transfers-api-openapi.yml
  format: yaml
  label: Dwolla Transfers API
  slug: dwolla-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-transfers-api-openapi.yml
- filename: dwolla-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Dwolla webhook subscriptions API
  slug: dwolla-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-webhook-subscriptions-api-openapi.yml
- filename: dwolla-webhooks-api-openapi.yml
  format: yaml
  label: Dwolla Webhooks API
  slug: dwolla-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must be (1) at least 18 years old and (2) a legal resident of the United States to create a Dwolla Account
  entity_types:
  - text: If you are creating a Dwolla Account as a natural person, you must be (1) at least 18 years old and (2) a legal resident of the United States to create a Dwolla Account.
    type: individual
  - text: Business Customers must be businesses (including sole proprietorships), non-profit organizations, and other entities registered and located in the United States.
    type: business
  minimum_age:
    text: you must be (1) at least 18 years old and (2) a legal resident of the United States to create a Dwolla Account
    value: '18'
  restricted_uses:
  - summary: Prohibited activities list
    text: Gun sellers and firearm or ammunition sales
  - summary: High-risk activity
    text: any activity we determine to be high risk or to expose us or other Dwolla clients or customers to an unacceptable level of risk
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: 'we will request that you provide additional information to permit us to verify your identity, including: your business entity type, a valid U.S. physical address'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dwolla
provenance_date: '2026-11-09'
provider_name: Dwolla
provider_slug: dwolla
slug: dwolla-eligibility
source_date: '2026-11-09'
source_filename: dwolla-eligibility.yml
source_heading: Eligibility
source_page: https://www.dwolla.com/legal/dwolla-account-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dwolla\naid: dwolla\nurl: https://www.dwolla.com/legal/dwolla-account-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must be (1) at least 18 years old and (2) a legal resident of the United States to create a Dwolla Account\nentity_types:\n- type: individual\n  text: If you are creating a Dwolla Account as a natural person, you must be (1) at least 18 years old and (2)\n    a legal resident of the United States to create a Dwolla Account.\n- type: business\n  text: Business Customers must be businesses (including sole proprietorships), non-profit organizations,\
  \ and other\n    entities registered and located in the United States.\nrestricted_uses:\n- summary: Prohibited activities list\n  text: Gun sellers and firearm or ammunition sales\n- summary: High-risk activity\n  text: any activity we determine to be high risk or to expose us or other Dwolla clients or customers to an unacceptable\n    level of risk\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: 'we will request that you provide additional information to permit us to verify your identity, including:\n    your business entity type, a valid U.S. physical address'\nminimum_age:\n  value: '18'\n  text: you must be (1) at least 18 years old and (2) a legal resident of the United States to create a Dwolla Account\n"
source_yaml_url: https://artifacts.apis.io/dwolla/eligibility/dwolla-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Dwolla's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- ACH
- Bank Transfers
- Fintech
- Account-to-Account Payments
- Money Movement
- Instant Payments
- Open Banking
- Webhook
- KYC
- United States
- Open Finance
- Same-Day ACH
- RTP
- FedNow
- Mass Payments
- Drop-in Components
- SDK
- Sandbox
---
