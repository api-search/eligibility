---
api_specs:
- filename: bykaranteli-x402-api-openapi.yml
  format: yaml
  label: ByKaranteli X402 API
  slug: bykaranteli-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-x402-api-openapi.yml
- filename: bykaranteli-public-api-openapi.yml
  format: yaml
  label: ByKaranteli Public API
  slug: bykaranteli-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-public-api-openapi.yml
- filename: bykaranteli-public-api-openapi.yml
  format: yaml
  label: ByKaranteli Public API
  slug: bykaranteli-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-public-api-openapi.yml
- filename: bykaranteli-series-api-openapi.yml
  format: yaml
  label: ByKaranteli Series API
  slug: bykaranteli-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-series-api-openapi.yml
- filename: bykaranteli-usage-api-openapi.yml
  format: yaml
  label: ByKaranteli Usage API
  slug: bykaranteli-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-usage-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not knowingly provide paid services to a person or entity located or ordinarily resident in a jurisdiction under comprehensive sanctions, or listed by the United Nations, the European Union, the United Kingdom or the United States Office of Foreign Assets Control.
  entity_types:
  - text: You must be at least 18 and legally able to enter a contract.
    type: individual
  - text: If you use the service in the course of a business, you will indemnify us against third-party claims
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export evasion
    text: Do not use the service to evade sanctions or export controls.
  - summary: Market manipulation via AI desk
    text: Do not use the desk to plan market manipulation
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
name: ByKaranteli
provenance_date: '2026-11-09'
provider_name: ByKaranteli
provider_slug: bykaranteli
slug: bykaranteli-eligibility
source_date: '2026-11-09'
source_filename: bykaranteli-eligibility.yml
source_heading: Eligibility
source_page: https://bykaranteli.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ByKaranteli\naid: bykaranteli\nurl: https://bykaranteli.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not knowingly provide paid services to a person or entity located or ordinarily resident in a jurisdiction\n    under comprehensive sanctions, or listed by the United Nations, the European Union, the United Kingdom or the\n    United States Office of Foreign Assets Control.\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to enter a contract.\n- type: business\n  text: If you use the service in the course of a business, you will\
  \ indemnify us against third-party claims\nrestricted_uses:\n- summary: Sanctions and export evasion\n  text: Do not use the service to evade sanctions or export controls.\n- summary: Market manipulation via AI desk\n  text: Do not use the desk to plan market manipulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/bykaranteli/eligibility/bykaranteli-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from ByKaranteli's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Crypto Derivatives
- Market Data
- Funding Rates
- Open Interest
- Liquidations
- Options
- ETF Flows
- Financial Data
- MCP
- x402
- Agents
---
