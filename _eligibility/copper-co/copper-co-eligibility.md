---
api_specs:
- filename: copper-co-accounts-api-openapi.yml
  format: yaml
  label: Copper.co Accounts API
  slug: copper-co-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-accounts-api-openapi.yml
- filename: copper-co-address-book-api-openapi.yml
  format: yaml
  label: Copper.co Address Book API
  slug: copper-co-address-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-address-book-api-openapi.yml
- filename: copper-co-blockchain-api-openapi.yml
  format: yaml
  label: Copper.co Blockchain API
  slug: copper-co-blockchain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-blockchain-api-openapi.yml
- filename: copper-co-clearloop-api-openapi.yml
  format: yaml
  label: Copper.co Clearloop API
  slug: copper-co-clearloop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-clearloop-api-openapi.yml
- filename: copper-co-currencies-api-openapi.yml
  format: yaml
  label: Copper.co Currencies API
  slug: copper-co-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-currencies-api-openapi.yml
- filename: copper-co-deposit-targets-api-openapi.yml
  format: yaml
  label: Copper.co Deposit Targets API
  slug: copper-co-deposit-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-deposit-targets-api-openapi.yml
- filename: copper-co-exchange-api-openapi.yml
  format: yaml
  label: Copper.co Exchange API
  slug: copper-co-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-exchange-api-openapi.yml
- filename: copper-co-files-api-openapi.yml
  format: yaml
  label: Copper.co Files API
  slug: copper-co-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-files-api-openapi.yml
- filename: copper-co-lending-api-openapi.yml
  format: yaml
  label: Copper.co Lending API
  slug: copper-co-lending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-lending-api-openapi.yml
- filename: copper-co-network-api-openapi.yml
  format: yaml
  label: Copper.co Network API
  slug: copper-co-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-network-api-openapi.yml
- filename: copper-co-orders-api-openapi.yml
  format: yaml
  label: Copper.co Orders API
  slug: copper-co-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-orders-api-openapi.yml
- filename: copper-co-organizations-api-openapi.yml
  format: yaml
  label: Copper.co Organizations API
  slug: copper-co-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-organizations-api-openapi.yml
- filename: copper-co-portfolios-api-openapi.yml
  format: yaml
  label: Copper.co Portfolios API
  slug: copper-co-portfolios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-portfolios-api-openapi.yml
- filename: copper-co-reports-api-openapi.yml
  format: yaml
  label: Copper.co Reports API
  slug: copper-co-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-reports-api-openapi.yml
- filename: copper-co-sign-async-api-openapi.yml
  format: yaml
  label: Copper.co Sign Async API
  slug: copper-co-sign-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-sign-async-api-openapi.yml
- filename: copper-co-stake-api-openapi.yml
  format: yaml
  label: Copper.co Stake API
  slug: copper-co-stake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-stake-api-openapi.yml
- filename: copper-co-trades-api-openapi.yml
  format: yaml
  label: Copper.co Trades API
  slug: copper-co-trades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-trades-api-openapi.yml
- filename: copper-co-wallets-api-openapi.yml
  format: yaml
  label: Copper.co Wallets API
  slug: copper-co-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper-co/openapi/copper-co-wallets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products and/or services described may not be available in your jurisdiction.
  entity_types:
  - text: Copper products and services are reserved for and will be provided to institutional investors with professional treasury management exclusively.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-institutional requests declined
    text: Any request for Copper products and services from any other person will be declined.
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
name: Copper.co
provenance_date: '2026-11-09'
provider_name: Copper.co
provider_slug: copper-co
slug: copper-co-eligibility
source_date: '2026-11-09'
source_filename: copper-co-eligibility.yml
source_heading: Eligibility
source_page: https://copper.co/en-ch/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copper.co\naid: copper-co\nurl: https://copper.co/en-ch/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The products and/or services described may not be available in your jurisdiction.\nentity_types:\n- type: business\n  text: Copper products and services are reserved for and will be provided to institutional investors with professional\n    treasury management exclusively.\nrestricted_uses:\n- summary: Non-institutional requests declined\n  text: Any request for Copper products and services from any other person will be declined.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/copper-co/eligibility/copper-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Copper.co's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Asset Custody
- Cryptocurrency
- Financial Services
- Institutional Finance
- Prime Brokerage
- Collateral Management
- Lending
- Settlement
- Staking
- Blockchain
- Treasury Management
- A2A
---
