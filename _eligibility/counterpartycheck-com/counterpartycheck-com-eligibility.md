---
api_specs:
- filename: counterpartycheck-com-account-api-openapi.yml
  format: yaml
  label: Counterparty Check Account API
  slug: counterpartycheck-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-account-api-openapi.yml
- filename: counterpartycheck-com-check-api-openapi.yml
  format: yaml
  label: Counterparty Check Check API
  slug: counterpartycheck-com-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-check-api-openapi.yml
- filename: counterpartycheck-com-mcp-api-openapi.yml
  format: yaml
  label: Counterparty Check MCP API
  slug: counterpartycheck-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-mcp-api-openapi.yml
- filename: counterpartycheck-com-pricing-api-openapi.yml
  format: yaml
  label: Counterparty Check Pricing API
  slug: counterpartycheck-com-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-pricing-api-openapi.yml
- filename: counterpartycheck-com-receipts-api-openapi.yml
  format: yaml
  label: Counterparty Check Receipts API
  slug: counterpartycheck-com-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-receipts-api-openapi.yml
- filename: counterpartycheck-com-screen-api-openapi.yml
  format: yaml
  label: Counterparty Check Screen API
  slug: counterpartycheck-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-screen-api-openapi.yml
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
  - summary: No consumer report uses
    text: You may not use the Service to determine any individual's eligibility for credit, insurance, employment, housing, or any other purpose covered by that Act or similar laws.
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
name: Counterparty Check
provenance_date: '2026-11-09'
provider_name: Counterparty Check
provider_slug: counterpartycheck-com
slug: counterpartycheck-com-eligibility
source_date: '2026-11-09'
source_filename: counterpartycheck-com-eligibility.yml
source_heading: Eligibility
source_page: https://counterpartycheck.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Counterparty Check\naid: counterpartycheck-com\nurl: https://counterpartycheck.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No consumer report uses\n  text: You may not use the Service to determine any individual's eligibility for credit, insurance, employment,\n    housing, or any other purpose covered by that Act or similar laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/counterpartycheck-com/eligibility/counterpartycheck-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Counterparty Check's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fraud Prevention
- Sanctions Screening
- Compliance
- AI Agents
- MCP
- x402
- Know Your Counterparty
---
