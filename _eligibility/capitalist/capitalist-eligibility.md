---
api_specs:
- filename: capitalist-capitalist-payments-api-api-openapi.yml
  format: yaml
  label: Capitalist Payments API (v1, deprecated)
  slug: capitalist-capitalist-payments-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capitalist/openapi/capitalist-capitalist-payments-api-api-openapi.yml
- filename: capitalist-account-api-openapi.yml
  format: yaml
  label: Capitalist Account API
  slug: capitalist-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capitalist/openapi/capitalist-account-api-openapi.yml
- filename: capitalist-exchange-api-openapi.yml
  format: yaml
  label: Capitalist Exchange API
  slug: capitalist-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capitalist/openapi/capitalist-exchange-api-openapi.yml
- filename: capitalist-payment-api-openapi.yml
  format: yaml
  label: Capitalist Payment API
  slug: capitalist-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capitalist/openapi/capitalist-payment-api-openapi.yml
- filename: capitalist-rate-api-openapi.yml
  format: yaml
  label: Capitalist Rate API
  slug: capitalist-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capitalist/openapi/capitalist-rate-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: addressed to physical and legal persons
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Referral program prohibitions
    text: Registering multiple accounts, accounts for own use, as well as re-registering users who previously had accounts in the System.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: According to the results of the Identification procedure, a certain status in the System is assigned to the Client.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Capitalist
provenance_date: '2026-11-09'
provider_name: Capitalist
provider_slug: capitalist
slug: capitalist-eligibility
source_date: '2026-11-09'
source_filename: capitalist-eligibility.yml
source_heading: Eligibility
source_page: https://capitalist.net/useragreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capitalist\naid: capitalist\nurl: https://capitalist.net/useragreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: addressed to physical and legal persons\nrestricted_uses:\n- summary: Referral program prohibitions\n  text: Registering multiple accounts, accounts for own use, as well as re-registering users who previously had\n    accounts in the System.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: According to the results of the Identification procedure, a certain status in the System is assigned\
  \ to\n    the Client.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/capitalist/eligibility/capitalist-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Capitalist's own page on 2026-11-09.
synthetic: false
tags:
- Bulk Payouts
- Cryptocurrency
- Finance
- Mass Payments
- Payment Platform
- Payments
- Payouts
- Remittances
---
