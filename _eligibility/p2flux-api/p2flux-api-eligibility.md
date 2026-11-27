---
api_specs:
- filename: p2flux-api-cancellation-api-openapi.yml
  format: yaml
  label: P2Flux API Cancellation API
  slug: p2flux-api-cancellation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-cancellation-api-openapi.yml
- filename: p2flux-api-one-time-payments-api-openapi.yml
  format: yaml
  label: P2Flux API One-time payments API
  slug: p2flux-api-one-time-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-one-time-payments-api-openapi.yml
- filename: p2flux-api-recurring-payments-api-openapi.yml
  format: yaml
  label: P2Flux API Recurring payments API
  slug: p2flux-api-recurring-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-recurring-payments-api-openapi.yml
- filename: p2flux-api-refunds-api-openapi.yml
  format: yaml
  label: P2Flux API Refunds API
  slug: p2flux-api-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-refunds-api-openapi.yml
- filename: p2flux-api-service-api-openapi.yml
  format: yaml
  label: P2Flux API Service API
  slug: p2flux-api-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-service-api-openapi.yml
- filename: p2flux-api-subscriptions-api-openapi.yml
  format: yaml
  label: P2Flux API Subscriptions API
  slug: p2flux-api-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-subscriptions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of a company or other organisation, you confirm that you have authority to accept these Terms on its behalf, and "you" refers to that organisation.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned wallets refused
    text: P2Flux does not process payments, subscriptions, refunds or payouts involving a wallet that appears on the U.S. OFAC Specially Designated Nationals list
  - summary: Unlawful use prohibited
    text: 'You may not knowingly use the Services: for unlawful activity; to violate applicable law or applicable sanctions; to facilitate fraud;'
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
name: P2Flux API
provenance_date: '2026-11-10'
provider_name: P2Flux API
provider_slug: p2flux-api
slug: p2flux-api-eligibility
source_date: '2026-11-10'
source_filename: p2flux-api-eligibility.yml
source_heading: Eligibility
source_page: https://p2flux.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: P2Flux API\naid: p2flux-api\nurl: https://p2flux.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company or other organisation, you confirm that you have authority\n    to accept these Terms on its behalf, and \"you\" refers to that organisation.\nrestricted_uses:\n- summary: Sanctioned wallets refused\n  text: P2Flux does not process payments, subscriptions, refunds or payouts involving a wallet that appears on the\n    U.S. OFAC Specially Designated Nationals list\n- summary:\
  \ Unlawful use prohibited\n  text: 'You may not knowingly use the Services: for unlawful activity; to violate applicable law or applicable\n    sanctions; to facilitate fraud;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/p2flux-api/eligibility/p2flux-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from P2Flux API's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment API
- Cryptocurrency
- Stablecoins
- USDC
- Base
- Recurring Payments
- Subscription
- Refunds
- Non-Custodial
---
