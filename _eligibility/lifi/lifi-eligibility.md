---
api_specs:
- filename: lifi-advanced-api-openapi.yml
  format: yaml
  label: LI.FI Advanced API
  slug: lifi-advanced-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-advanced-api-openapi.yml
- filename: lifi-analytics-api-openapi.yml
  format: yaml
  label: LI.FI Analytics API
  slug: lifi-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-analytics-api-openapi.yml
- filename: lifi-chains-api-openapi.yml
  format: yaml
  label: LI.FI Chains API
  slug: lifi-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-chains-api-openapi.yml
- filename: lifi-connections-api-openapi.yml
  format: yaml
  label: LI.FI Connections API
  slug: lifi-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-connections-api-openapi.yml
- filename: lifi-earn-chains-api-openapi.yml
  format: yaml
  label: LI.FI Earn Chains API
  slug: lifi-earn-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-earn-chains-api-openapi.yml
- filename: lifi-earn-portfolio-api-openapi.yml
  format: yaml
  label: LI.FI Earn Portfolio API
  slug: lifi-earn-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-earn-portfolio-api-openapi.yml
- filename: lifi-earn-protocols-api-openapi.yml
  format: yaml
  label: LI.FI Earn Protocols API
  slug: lifi-earn-protocols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-earn-protocols-api-openapi.yml
- filename: lifi-earn-vaults-api-openapi.yml
  format: yaml
  label: LI.FI Earn Vaults API
  slug: lifi-earn-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-earn-vaults-api-openapi.yml
- filename: lifi-gas-api-openapi.yml
  format: yaml
  label: LI.FI Gas API
  slug: lifi-gas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-gas-api-openapi.yml
- filename: lifi-integrators-api-openapi.yml
  format: yaml
  label: LI.FI Integrators API
  slug: lifi-integrators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-integrators-api-openapi.yml
- filename: lifi-quote-api-openapi.yml
  format: yaml
  label: LI.FI Quote API
  slug: lifi-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-quote-api-openapi.yml
- filename: lifi-relayer-api-openapi.yml
  format: yaml
  label: LI.FI Relayer API
  slug: lifi-relayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-relayer-api-openapi.yml
- filename: lifi-status-api-openapi.yml
  format: yaml
  label: LI.FI Status API
  slug: lifi-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-status-api-openapi.yml
- filename: lifi-token-api-openapi.yml
  format: yaml
  label: LI.FI Token API
  slug: lifi-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-token-api-openapi.yml
- filename: lifi-tokens-api-openapi.yml
  format: yaml
  label: LI.FI Tokens API
  slug: lifi-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-tokens-api-openapi.yml
- filename: lifi-tools-api-openapi.yml
  format: yaml
  label: LI.FI Tools API
  slug: lifi-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-tools-api-openapi.yml
- filename: lifi-call-data-api-openapi.yml
  format: yaml
  label: LI.FI Call Data API
  slug: lifi-call-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifi/openapi/lifi-call-data-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: User further warrants that User is not a United States citizen, permanent resident alien, entity organised under the laws of the United States or any jurisdiction within the United States (including foreign branches), or any person in the United States.
  entity_types:
  - text: For Users who are merchants (Kaufleute) within the meaning of the German Commercial Code (Handelsgesetzbuch), a special fund (Sondervermögen) under public law or a legal entity under public law, Berlin, Germany, shall be the exclusive place of jurisdiction for all disputes arising from the contractual relationship.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned parties and jurisdictions
    text: User warrants that they are not (i) subject to any economic or trade sanctions imposed by any government agency or listed on any prohibited or restricted party list
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
name: LI.FI
provenance_date: '2026-11-09'
provider_name: LI.FI
provider_slug: lifi
slug: lifi-eligibility
source_date: '2026-11-09'
source_filename: lifi-eligibility.yml
source_heading: Eligibility
source_page: https://li.fi/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LI.FI\naid: lifi\nurl: https://li.fi/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: User further warrants that User is not a United States citizen, permanent resident alien, entity organised\n    under the laws of the United States or any jurisdiction within the United States (including foreign branches),\n    or any person in the United States.\nentity_types:\n- type: business\n  text: For Users who are merchants (Kaufleute) within the meaning of the German Commercial Code (Handelsgesetzbuch),\n    a special fund (Sondervermögen) under public law or a\
  \ legal entity under public law, Berlin, Germany, shall\n    be the exclusive place of jurisdiction for all disputes arising from the contractual relationship.\nrestricted_uses:\n- summary: Sanctioned parties and jurisdictions\n  text: User warrants that they are not (i) subject to any economic or trade sanctions imposed by any government\n    agency or listed on any prohibited or restricted party list\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lifi/eligibility/lifi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LI.FI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- Blockchain
- Cross-Chain
- Bridge
- DEX Aggregation
- DeFi
- Payments
- Liquidity
- Yield
- Intents
- Agents
- Cryptocurrency
---
