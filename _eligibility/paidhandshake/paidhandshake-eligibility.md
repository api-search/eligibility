---
api_specs:
- filename: paidhandshake-capabilities-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Capabilities API
  slug: paidhandshake-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-capabilities-api-openapi.yml
- filename: paidhandshake-checkout-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Checkout API
  slug: paidhandshake-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-checkout-api-openapi.yml
- filename: paidhandshake-inventory-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Inventory API
  slug: paidhandshake-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-inventory-api-openapi.yml
- filename: paidhandshake-machine-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Machine API
  slug: paidhandshake-machine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-machine-api-openapi.yml
- filename: paidhandshake-proof-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Proof API
  slug: paidhandshake-proof-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-proof-api-openapi.yml
- filename: paidhandshake-quote-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Quote API
  slug: paidhandshake-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-quote-api-openapi.yml
- filename: paidhandshake-sample-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Sample API
  slug: paidhandshake-sample-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-sample-api-openapi.yml
- filename: paidhandshake-search-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange Search API
  slug: paidhandshake-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-search-api-openapi.yml
- filename: paidhandshake-well-known-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange .well Known API
  slug: paidhandshake-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-well-known-api-openapi.yml
- filename: paidhandshake-x402-api-openapi.yml
  format: yaml
  label: PaidHandshake Exchange X402 API
  slug: paidhandshake-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidhandshake/openapi/paidhandshake-x402-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited brokering
    text: PaidHandshake may not be used to broker illegal drugs, weapons trafficking, stolen or counterfeit goods, sexual exploitation, private personal information, credential theft, fraud or other unlawful or abusive transactions.
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
name: PaidHandshake Exchange
provenance_date: '2026-11-10'
provider_name: PaidHandshake Exchange
provider_slug: paidhandshake
slug: paidhandshake-eligibility
source_date: '2026-11-10'
source_filename: paidhandshake-eligibility.yml
source_heading: Eligibility
source_page: https://paidhandshake.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PaidHandshake Exchange\naid: paidhandshake\nurl: https://paidhandshake.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited brokering\n  text: PaidHandshake may not be used to broker illegal drugs, weapons trafficking, stolen or counterfeit goods,\n    sexual exploitation, private personal information, credential theft, fraud or other unlawful or abusive transactions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paidhandshake/eligibility/paidhandshake-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from PaidHandshake Exchange's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketplace
- Data
- Automation
---
