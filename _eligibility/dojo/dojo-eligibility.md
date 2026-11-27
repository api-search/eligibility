---
api_specs:
- filename: dojo-areas-api-openapi.yml
  format: yaml
  label: Dojo Areas API
  slug: dojo-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-areas-api-openapi.yml
- filename: dojo-capabilities-api-openapi.yml
  format: yaml
  label: Dojo Capabilities API
  slug: dojo-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-capabilities-api-openapi.yml
- filename: dojo-captures-api-openapi.yml
  format: yaml
  label: Dojo Captures API
  slug: dojo-captures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-captures-api-openapi.yml
- filename: dojo-customers-api-openapi.yml
  format: yaml
  label: Dojo Customers API
  slug: dojo-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-customers-api-openapi.yml
- filename: dojo-events-api-openapi.yml
  format: yaml
  label: Dojo Events API
  slug: dojo-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-events-api-openapi.yml
- filename: dojo-flows-api-openapi.yml
  format: yaml
  label: Dojo Flows API
  slug: dojo-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-flows-api-openapi.yml
- filename: dojo-orders-api-openapi.yml
  format: yaml
  label: Dojo Orders API
  slug: dojo-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-orders-api-openapi.yml
- filename: dojo-parties-api-openapi.yml
  format: yaml
  label: Dojo Parties API
  slug: dojo-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-parties-api-openapi.yml
- filename: dojo-payment-intents-api-openapi.yml
  format: yaml
  label: Dojo Payment intents API
  slug: dojo-payment-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-payment-intents-api-openapi.yml
- filename: dojo-refunds-api-openapi.yml
  format: yaml
  label: Dojo Refunds API
  slug: dojo-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-refunds-api-openapi.yml
- filename: dojo-reservations-api-openapi.yml
  format: yaml
  label: Dojo Reservations API
  slug: dojo-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-reservations-api-openapi.yml
- filename: dojo-reversal-api-openapi.yml
  format: yaml
  label: Dojo Reversal API
  slug: dojo-reversal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-reversal-api-openapi.yml
- filename: dojo-setup-intents-api-openapi.yml
  format: yaml
  label: Dojo Setup intents API
  slug: dojo-setup-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-setup-intents-api-openapi.yml
- filename: dojo-tables-api-openapi.yml
  format: yaml
  label: Dojo Tables API
  slug: dojo-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-tables-api-openapi.yml
- filename: dojo-tap-to-pay-on-iphone-api-openapi.yml
  format: yaml
  label: Dojo Tap to Pay on iPhone API
  slug: dojo-tap-to-pay-on-iphone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-tap-to-pay-on-iphone-api-openapi.yml
- filename: dojo-terminal-sessions-api-openapi.yml
  format: yaml
  label: Dojo Terminal sessions API
  slug: dojo-terminal-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-terminal-sessions-api-openapi.yml
- filename: dojo-terminals-api-openapi.yml
  format: yaml
  label: Dojo Terminals API
  slug: dojo-terminals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-terminals-api-openapi.yml
- filename: dojo-transactions-api-openapi.yml
  format: yaml
  label: Dojo Transactions API
  slug: dojo-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-transactions-api-openapi.yml
- filename: dojo-webhooks-api-openapi.yml
  format: yaml
  label: Dojo Webhooks API
  slug: dojo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dojo/openapi/dojo-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an electronic point-of-sale partner and have a separate agreement with us relating to the Dojo Tools, any terms in that separate agreement which conflict with those terms shall prevail.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use and access our Dojo Tools, you must have or create an account with us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dojo
provenance_date: '2026-11-09'
provider_name: Dojo
provider_slug: dojo
slug: dojo-eligibility
source_date: '2026-11-09'
source_filename: dojo-eligibility.yml
source_heading: Eligibility
source_page: https://docs.dojo.tech/development-resources/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dojo\naid: dojo\nurl: https://docs.dojo.tech/development-resources/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an electronic point-of-sale partner and have a separate agreement with us relating to the Dojo\n    Tools, any terms in that separate agreement which conflict with those terms shall prevail.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use and access our Dojo Tools, you must have or create an account with us.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dojo/eligibility/dojo-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Dojo's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- In-Person Payments
- Point-of-Sale
- Webhook
- Real-Time
- Payment Terminals
---
