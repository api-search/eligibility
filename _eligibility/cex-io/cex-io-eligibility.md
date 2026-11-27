---
api_specs:
- filename: cex-io-accounts-api-openapi.yml
  format: yaml
  label: CEX.IO Accounts API
  slug: cex-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-accounts-api-openapi.yml
- filename: cex-io-fees-api-openapi.yml
  format: yaml
  label: CEX.IO Fees API
  slug: cex-io-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-fees-api-openapi.yml
- filename: cex-io-funding-api-openapi.yml
  format: yaml
  label: CEX.IO Funding API
  slug: cex-io-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-funding-api-openapi.yml
- filename: cex-io-history-api-openapi.yml
  format: yaml
  label: CEX.IO History API
  slug: cex-io-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-history-api-openapi.yml
- filename: cex-io-market-data-api-openapi.yml
  format: yaml
  label: CEX.IO Market Data API
  slug: cex-io-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-market-data-api-openapi.yml
- filename: cex-io-orders-api-openapi.yml
  format: yaml
  label: CEX.IO Orders API
  slug: cex-io-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-orders-api-openapi.yml
- filename: cex-io-private-api-openapi.yml
  format: yaml
  label: CEX.IO Private API
  slug: cex-io-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-private-api-openapi.yml
- filename: cex-io-public-api-openapi.yml
  format: yaml
  label: CEX.IO Public API
  slug: cex-io-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-public-api-openapi.yml
- filename: cex-io-public-market-data-api-openapi.yml
  format: yaml
  label: CEX.IO Public Market Data API
  slug: cex-io-public-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-public-market-data-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: any person located in the United States of America that registers for and/or opens a CEX.IO Account
  entity_types:
  - text: such a legal entity shall register a corporate account with CEX.IO and you shall not use your individual account for business purposes.
    type: business
  minimum_age:
    text: are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Restricted location
    text: are not located in a Restricted Location
  - summary: Prohibited transactions and activities
    text: CEX.IO does not provide services for transactions related to the prohibited industries, and business activities outlined below
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Identification and verification procedures (also known as 'Know Your Customer' or 'KYC') are required for all Transactions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CEX.IO
provenance_date: '2026-11-09'
provider_name: CEX.IO
provider_slug: cex-io
slug: cex-io-eligibility
source_date: '2026-11-09'
source_filename: cex-io-eligibility.yml
source_heading: Eligibility
source_page: https://cex.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CEX.IO\naid: cex-io\nurl: https://cex.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: any person located in the United States of America that registers for and/or opens a CEX.IO Account\nentity_types:\n- type: business\n  text: such a legal entity shall register a corporate account with CEX.IO and you shall not use your individual\n    account for business purposes.\nrestricted_uses:\n- summary: Restricted location\n  text: are not located in a Restricted Location\n- summary: Prohibited transactions and activities\n  text: CEX.IO does not provide\
  \ services for transactions related to the prohibited industries, and business activities\n    outlined below\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Identification and verification procedures (also known as 'Know Your Customer' or 'KYC') are required for\n    all Transactions.\nminimum_age:\n  value: '18'\n  text: are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/cex-io/eligibility/cex-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CEX.IO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Market Data
- WebSocket
- Financial Services
---
