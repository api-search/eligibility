---
api_specs:
- filename: bvnk-address-api-openapi.yml
  format: yaml
  label: BVNK Address API
  slug: bvnk-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-address-api-openapi.yml
- filename: bvnk-asset-pool-api-openapi.yml
  format: yaml
  label: BVNK Asset Pool API
  slug: bvnk-asset-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-asset-pool-api-openapi.yml
- filename: bvnk-channels-api-openapi.yml
  format: yaml
  label: BVNK Channels API
  slug: bvnk-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-channels-api-openapi.yml
- filename: bvnk-currencies-api-openapi.yml
  format: yaml
  label: BVNK Currencies API
  slug: bvnk-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-currencies-api-openapi.yml
- filename: bvnk-export-api-openapi.yml
  format: yaml
  label: BVNK Export API
  slug: bvnk-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-export-api-openapi.yml
- filename: bvnk-fee-api-openapi.yml
  format: yaml
  label: BVNK Fee API
  slug: bvnk-fee-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-fee-api-openapi.yml
- filename: bvnk-key-pair-api-openapi.yml
  format: yaml
  label: BVNK Key Pair API
  slug: bvnk-key-pair-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-key-pair-api-openapi.yml
- filename: bvnk-merchant-ids-api-openapi.yml
  format: yaml
  label: BVNK Merchant IDs API
  slug: bvnk-merchant-ids-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-merchant-ids-api-openapi.yml
- filename: bvnk-network-api-openapi.yml
  format: yaml
  label: BVNK Network API
  slug: bvnk-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-network-api-openapi.yml
- filename: bvnk-payments-api-openapi.yml
  format: yaml
  label: BVNK Payments API
  slug: bvnk-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-payments-api-openapi.yml
- filename: bvnk-return-api-openapi.yml
  format: yaml
  label: BVNK Return API
  slug: bvnk-return-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-return-api-openapi.yml
- filename: bvnk-screening-api-openapi.yml
  format: yaml
  label: BVNK Screening API
  slug: bvnk-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-screening-api-openapi.yml
- filename: bvnk-trading-and-conversions-api-openapi.yml
  format: yaml
  label: BVNK Trading and Conversions API
  slug: bvnk-trading-and-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-trading-and-conversions-api-openapi.yml
- filename: bvnk-transaction-api-openapi.yml
  format: yaml
  label: BVNK Transaction API
  slug: bvnk-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-transaction-api-openapi.yml
- filename: bvnk-transaction-request-api-openapi.yml
  format: yaml
  label: BVNK Transaction Request API
  slug: bvnk-transaction-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-transaction-request-api-openapi.yml
- filename: bvnk-wallets-api-openapi.yml
  format: yaml
  label: BVNK Wallets API
  slug: bvnk-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bvnk/openapi/bvnk-wallets-api-openapi.yml
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
  - summary: Lawful purposes only
    text: You may use the BVNK website only for lawful purposes.
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
name: BVNK
provenance_date: '2026-11-09'
provider_name: BVNK
provider_slug: bvnk
slug: bvnk-eligibility
source_date: '2026-11-09'
source_filename: bvnk-eligibility.yml
source_heading: Eligibility
source_page: https://help.bvnk.com/hc/en-us/articles/7662073461394-Website-Terms-of-Use-Cookies-Policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BVNK\naid: bvnk\nurl: https://help.bvnk.com/hc/en-us/articles/7662073461394-Website-Terms-of-Use-Cookies-Policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the BVNK website only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bvnk/eligibility/bvnk-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BVNK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Stablecoins
- Cryptocurrency
- Wallets
- Virtual Accounts
- Cross-Border Payments
- Financial Services
- Cards
- Digital Assets
- Banking
- Compliance
---
