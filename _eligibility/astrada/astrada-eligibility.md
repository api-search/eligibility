---
api_specs:
- filename: astrada-bank-accounts-api-openapi.yml
  format: yaml
  label: Astrada Bank Accounts API
  slug: astrada-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-bank-accounts-api-openapi.yml
- filename: astrada-bank-links-api-openapi.yml
  format: yaml
  label: Astrada Bank Links API
  slug: astrada-bank-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-bank-links-api-openapi.yml
- filename: astrada-bank-subscriptions-api-openapi.yml
  format: yaml
  label: Astrada Bank Subscriptions API
  slug: astrada-bank-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-bank-subscriptions-api-openapi.yml
- filename: astrada-bank-transactions-api-openapi.yml
  format: yaml
  label: Astrada Bank Transactions API
  slug: astrada-bank-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-bank-transactions-api-openapi.yml
- filename: astrada-bin-lookup-api-openapi.yml
  format: yaml
  label: Astrada Bin Lookup API
  slug: astrada-bin-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-bin-lookup-api-openapi.yml
- filename: astrada-card-api-openapi.yml
  format: yaml
  label: Astrada Card API
  slug: astrada-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-card-api-openapi.yml
- filename: astrada-card-subscription-api-openapi.yml
  format: yaml
  label: Astrada Card Subscription API
  slug: astrada-card-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-card-subscription-api-openapi.yml
- filename: astrada-card-verification-api-openapi.yml
  format: yaml
  label: Astrada Card Verification API
  slug: astrada-card-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-card-verification-api-openapi.yml
- filename: astrada-enrollment-methods-api-openapi.yml
  format: yaml
  label: Astrada Enrollment Methods API
  slug: astrada-enrollment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-enrollment-methods-api-openapi.yml
- filename: astrada-network-bulk-feeds-api-openapi.yml
  format: yaml
  label: Astrada Network Bulk Feeds API
  slug: astrada-network-bulk-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-network-bulk-feeds-api-openapi.yml
- filename: astrada-subaccounts-api-openapi.yml
  format: yaml
  label: Astrada Subaccounts API
  slug: astrada-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-subaccounts-api-openapi.yml
- filename: astrada-transaction-matches-api-openapi.yml
  format: yaml
  label: Astrada Transaction Matches API
  slug: astrada-transaction-matches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-transaction-matches-api-openapi.yml
- filename: astrada-transaction-messages-api-openapi.yml
  format: yaml
  label: Astrada Transaction Messages API
  slug: astrada-transaction-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-transaction-messages-api-openapi.yml
- filename: astrada-transactions-api-openapi.yml
  format: yaml
  label: Astrada Transactions API
  slug: astrada-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-transactions-api-openapi.yml
- filename: astrada-webhooks-api-openapi.yml
  format: yaml
  label: Astrada Webhooks API
  slug: astrada-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrada/openapi/astrada-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Astrada provides the following components to third party providers of transaction data-enabled services ("Clients")
    type: business
  minimum_age:
    text: The Service is not directed at persons under 13 and we do not knowingly collect personal information from children.
    value: null
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
name: Astrada
provenance_date: '2026-11-09'
provider_name: Astrada
provider_slug: astrada
slug: astrada-eligibility
source_date: '2026-11-09'
source_filename: astrada-eligibility.yml
source_heading: Eligibility
source_page: https://astrada.co/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astrada\naid: astrada\nurl: https://astrada.co/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Astrada provides the following components to third party providers of transaction data-enabled services\n    (\"Clients\")\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Service is not directed at persons under 13 and we do not knowingly collect personal information from\n    children.\n"
source_yaml_url: https://artifacts.apis.io/astrada/eligibility/astrada-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Astrada's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Card Data
- Transaction Data
- Reconciliation
- Expense Management
- Data Infrastructure
---
