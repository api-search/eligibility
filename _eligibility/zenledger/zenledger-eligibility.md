---
api_specs:
- filename: zenledger-authentication-api-openapi.yml
  format: yaml
  label: ZenLedger Authentication API
  slug: zenledger-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-authentication-api-openapi.yml
- filename: zenledger-companies-api-openapi.yml
  format: yaml
  label: ZenLedger Companies API
  slug: zenledger-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-companies-api-openapi.yml
- filename: zenledger-holdings-api-openapi.yml
  format: yaml
  label: ZenLedger Holdings API
  slug: zenledger-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-holdings-api-openapi.yml
- filename: zenledger-imports-api-openapi.yml
  format: yaml
  label: ZenLedger Imports API
  slug: zenledger-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-imports-api-openapi.yml
- filename: zenledger-polymarkets-api-openapi.yml
  format: yaml
  label: ZenLedger Polymarkets API
  slug: zenledger-polymarkets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-polymarkets-api-openapi.yml
- filename: zenledger-portfolios-api-openapi.yml
  format: yaml
  label: ZenLedger Portfolios API
  slug: zenledger-portfolios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-portfolios-api-openapi.yml
- filename: zenledger-supported-chains-api-openapi.yml
  format: yaml
  label: ZenLedger Supported Chains API
  slug: zenledger-supported-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-supported-chains-api-openapi.yml
- filename: zenledger-supported-currencies-api-openapi.yml
  format: yaml
  label: ZenLedger Supported Currencies API
  slug: zenledger-supported-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-supported-currencies-api-openapi.yml
- filename: zenledger-supported-exchanges-and-wallets-api-openapi.yml
  format: yaml
  label: ZenLedger Supported Exchanges and Wallets API
  slug: zenledger-supported-exchanges-and-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-supported-exchanges-and-wallets-api-openapi.yml
- filename: zenledger-taxes-api-openapi.yml
  format: yaml
  label: ZenLedger Taxes API
  slug: zenledger-taxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-taxes-api-openapi.yml
- filename: zenledger-transactions-api-openapi.yml
  format: yaml
  label: ZenLedger Transactions API
  slug: zenledger-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-transactions-api-openapi.yml
- filename: zenledger-users-api-openapi.yml
  format: yaml
  label: ZenLedger Users API
  slug: zenledger-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-users-api-openapi.yml
- filename: zenledger-wallet-screening-api-openapi.yml
  format: yaml
  label: ZenLedger Wallet Screening API
  slug: zenledger-wallet-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenledger/openapi/zenledger-wallet-screening-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are representing and warranting that You are not located in, under the control of, or a national or resident of any restricted country or on any such list.
  entity_types:
  - text: You may not accept this Agreement if You are not legally authorized to accept and be bound by these terms or are not at least 18 years of age
    type: individual
  minimum_age:
    text: are not at least 18 years of age and, inany event, of a legal age to form a binding contract with ZenLedger.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You shall comply with all export laws and restrictions and regulations of the United States Department of Commerce or any other United States or foreign agency or authority
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In that registration process, We require that You provide only Your email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ZenLedger
provenance_date: '2026-11-10'
provider_name: ZenLedger
provider_slug: zenledger
slug: zenledger-eligibility
source_date: '2026-11-10'
source_filename: zenledger-eligibility.yml
source_heading: Eligibility
source_page: https://zenledger.io/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZenLedger\naid: zenledger\nurl: https://zenledger.io/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are representing and warranting that You are not located in, under the control of, or a national or\n    resident of any restricted country or on any such list.\nentity_types:\n- type: individual\n  text: You may not accept this Agreement if You are not legally authorized to accept and be bound by these terms\n    or are not at least 18 years of age\nrestricted_uses:\n- summary: Export restrictions\n  text: You shall comply with all export laws and restrictions and\
  \ regulations of the United States Department of\n    Commerce or any other United States or foreign agency or authority\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In that registration process, We require that You provide only Your email address.\nminimum_age:\n  value: '18'\n  text: are not at least 18 years of age and, inany event, of a legal age to form a binding contract with ZenLedger.\n"
source_yaml_url: https://artifacts.apis.io/zenledger/eligibility/zenledger-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ZenLedger's own page on 2026-11-10.
synthetic: false
tags:
- crypto-tax
- Digital Assets
- Tax Compliance
- Blockchain Analytics
- RegTech
- Accounting
- Sanctions Screening
- Financial Services
- Portfolio Aggregation
- Cryptocurrency
---
