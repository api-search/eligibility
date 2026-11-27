---
api_specs:
- filename: utila-address-book-api-openapi.yml
  format: yaml
  label: Utila Address Book API
  slug: utila-address-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utila/openapi/utila-address-book-api-openapi.yml
- filename: utila-assets-api-openapi.yml
  format: yaml
  label: Utila Assets API
  slug: utila-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utila/openapi/utila-assets-api-openapi.yml
- filename: utila-balances-api-openapi.yml
  format: yaml
  label: Utila Balances API
  slug: utila-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utila/openapi/utila-balances-api-openapi.yml
- filename: utila-blockchains-api-openapi.yml
  format: yaml
  label: Utila Blockchains API
  slug: utila-blockchains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utila/openapi/utila-blockchains-api-openapi.yml
- filename: utila-transactions-api-openapi.yml
  format: yaml
  label: Utila Transactions API
  slug: utila-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utila/openapi/utila-transactions-api-openapi.yml
- filename: utila-vaults-api-openapi.yml
  format: yaml
  label: Utila Vaults API
  slug: utila-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utila/openapi/utila-vaults-api-openapi.yml
- filename: utila-wallets-api-openapi.yml
  format: yaml
  label: Utila Wallets API
  slug: utila-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utila/openapi/utila-wallets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of and access to the Site is void where prohibited by law.
  minimum_age:
    text: By using the Site, you represent and warrant that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Use must comply with applicable law
    text: your use of the Site does not violate any applicable law or regulation or any obligation.
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
name: Utila
provenance_date: '2026-11-10'
provider_name: Utila
provider_slug: utila
slug: utila-eligibility
source_date: '2026-11-10'
source_filename: utila-eligibility.yml
source_heading: Eligibility
source_page: https://utila.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Utila\naid: utila\nurl: https://utila.io/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of and access to the Site is void where prohibited by law.\nentity_types: []\nrestricted_uses:\n- summary: Use must comply with applicable law\n  text: your use of the Site does not violate any applicable law or regulation or any obligation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Site, you represent and warrant that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/utila/eligibility/utila-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Utila's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- Digital Assets
- Stablecoins
- Custody
- MPC Wallets
- Blockchain
- Payments
- Treasury
---
