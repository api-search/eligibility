---
api_specs:
- filename: blnkfinance-accounts-api-openapi.yml
  format: yaml
  label: Blnk Finance Accounts API
  slug: blnkfinance-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-accounts-api-openapi.yml
- filename: blnkfinance-backup-api-openapi.yml
  format: yaml
  label: Blnk Finance Backup API
  slug: blnkfinance-backup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-backup-api-openapi.yml
- filename: blnkfinance-balance-monitors-api-openapi.yml
  format: yaml
  label: Blnk Finance Balance Monitors API
  slug: blnkfinance-balance-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-balance-monitors-api-openapi.yml
- filename: blnkfinance-balances-api-openapi.yml
  format: yaml
  label: Blnk Finance Balances API
  slug: blnkfinance-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-balances-api-openapi.yml
- filename: blnkfinance-identities-api-openapi.yml
  format: yaml
  label: Blnk Finance Identities API
  slug: blnkfinance-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-identities-api-openapi.yml
- filename: blnkfinance-ledgers-api-openapi.yml
  format: yaml
  label: Blnk Finance Ledgers API
  slug: blnkfinance-ledgers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-ledgers-api-openapi.yml
- filename: blnkfinance-refund-transaction-api-openapi.yml
  format: yaml
  label: Blnk Finance Refund Transaction API
  slug: blnkfinance-refund-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-refund-transaction-api-openapi.yml
- filename: blnkfinance-transactions-api-openapi.yml
  format: yaml
  label: Blnk Finance Transactions API
  slug: blnkfinance-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-transactions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organisation, you represent and warrant that you have the authority to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: you represent and warrant that you are at least 18 years old and have the legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: No unlawful or fraudulent activities
    text: Use the Services to conduct any unlawful or fraudulent activities.
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
name: Blnk Finance
provenance_date: '2026-11-09'
provider_name: Blnk Finance
provider_slug: blnkfinance
slug: blnkfinance-eligibility
source_date: '2026-11-09'
source_filename: blnkfinance-eligibility.yml
source_heading: Eligibility
source_page: https://blnkfinance.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blnk Finance\naid: blnkfinance\nurl: https://blnkfinance.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organisation, you represent and warrant that you have the\n    authority to bind that organisation to these Terms.\nrestricted_uses:\n- summary: No unlawful or fraudulent activities\n  text: Use the Services to conduct any unlawful or fraudulent activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: you represent and warrant that you are at least 18 years old and have the legal capacity to enter into these\n    Terms.\n"
source_yaml_url: https://artifacts.apis.io/blnkfinance/eligibility/blnkfinance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Blnk Finance's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Financial Services
- Ledger
- Double-Entry
- Payments
- Wallets
- Lending
- Banking Infrastructure
- Open Source
- MCP
- AI Agents
- Developer Tools
- A2A
---
