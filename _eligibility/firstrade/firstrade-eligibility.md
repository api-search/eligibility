---
api_specs:
- filename: firstrade-plaid-api-openapi.yml
  format: yaml
  label: Firstrade Plaid API
  slug: firstrade-plaid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firstrade/openapi/firstrade-plaid-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This is not an offer or solicitation in any jurisdiction where Firstrade is not authorized to conduct securities transaction.
  entity_types:
  - text: Build your family's wealth with an Individual or Joint brokerage account.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Options trading privileges are subject to Firstrade review and approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Firstrade
provenance_date: '2026-11-09'
provider_name: Firstrade
provider_slug: firstrade
slug: firstrade-eligibility
source_date: '2026-11-09'
source_filename: firstrade-eligibility.yml
source_heading: Eligibility
source_page: https://www.firstrade.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firstrade\naid: firstrade\nurl: https://www.firstrade.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This is not an offer or solicitation in any jurisdiction where Firstrade is not authorized to conduct securities\n    transaction.\nentity_types:\n- type: individual\n  text: Build your family's wealth with an Individual or Joint brokerage account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Options trading privileges are subject to Firstrade review and approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firstrade/eligibility/firstrade-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Firstrade's own page on 2026-11-09.
synthetic: false
tags:
- Brokerage
- Commission-Free Trading
- Stocks
- ETFs
- Options
- Mutual Funds
- Fixed Income
- Retirement
- IRA
- Investing
- Finance
- Open Banking
- Financial Services
---
