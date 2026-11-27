---
api_specs:
- filename: ibanfirst-accounts-api-openapi.yml
  format: yaml
  label: iBanFirst Accounts API
  slug: ibanfirst-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-accounts-api-openapi.yml
- filename: ibanfirst-beneficiaries-api-openapi.yml
  format: yaml
  label: iBanFirst Beneficiaries API
  slug: ibanfirst-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-beneficiaries-api-openapi.yml
- filename: ibanfirst-documents-api-openapi.yml
  format: yaml
  label: iBanFirst Documents API
  slug: ibanfirst-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-documents-api-openapi.yml
- filename: ibanfirst-financial-movements-api-openapi.yml
  format: yaml
  label: iBanFirst Financial movements API
  slug: ibanfirst-financial-movements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-financial-movements-api-openapi.yml
- filename: ibanfirst-fixed-forward-payment-contract-api-openapi.yml
  format: yaml
  label: iBanFirst Fixed forward payment contract API
  slug: ibanfirst-fixed-forward-payment-contract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-fixed-forward-payment-contract-api-openapi.yml
- filename: ibanfirst-logs-api-openapi.yml
  format: yaml
  label: iBanFirst Logs API
  slug: ibanfirst-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-logs-api-openapi.yml
- filename: ibanfirst-payments-api-openapi.yml
  format: yaml
  label: iBanFirst Payments API
  slug: ibanfirst-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-payments-api-openapi.yml
- filename: ibanfirst-spot-trades-api-openapi.yml
  format: yaml
  label: iBanFirst Spot trades API
  slug: ibanfirst-spot-trades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-spot-trades-api-openapi.yml
- filename: ibanfirst-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: iBanFirst Webhook subscriptions API
  slug: ibanfirst-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-webhook-subscriptions-api-openapi.yml
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
  - summary: No options or investment/speculative instruments
    text: iBanFirst S.A. does not offer options or any other financial instruments for investment or speculative purposes.
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
name: iBanFirst
provenance_date: '2026-11-09'
provider_name: iBanFirst
provider_slug: ibanfirst
slug: ibanfirst-eligibility
source_date: '2026-11-09'
source_filename: ibanfirst-eligibility.yml
source_heading: Eligibility
source_page: https://ibanfirst.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iBanFirst\naid: ibanfirst\nurl: https://ibanfirst.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No options or investment/speculative instruments\n  text: iBanFirst S.A. does not offer options or any other financial instruments for investment or speculative purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ibanfirst/eligibility/ibanfirst-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from iBanFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech Insurtech
- Cross-Border Payments
- Foreign Exchange
- B2B Payments
- Treasury
- Multi‑Currency Accounts
- SEPA
- PSD2
- Open Banking
- currency-risk-management
- Webhook
- MCP
- Belgium
- Europe
- SWIFT
---
