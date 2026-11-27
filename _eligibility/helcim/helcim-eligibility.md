---
api_specs:
- filename: helcim-ach-payment-api-openapi.yml
  format: yaml
  label: Helcim ACH Payment API
  slug: helcim-ach-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-ach-payment-api-openapi.yml
- filename: helcim-card-batch-api-openapi.yml
  format: yaml
  label: Helcim Card Batch API
  slug: helcim-card-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-card-batch-api-openapi.yml
- filename: helcim-card-terminal-api-openapi.yml
  format: yaml
  label: Helcim Card Terminal API
  slug: helcim-card-terminal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-card-terminal-api-openapi.yml
- filename: helcim-card-transaction-api-openapi.yml
  format: yaml
  label: Helcim Card Transaction API
  slug: helcim-card-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-card-transaction-api-openapi.yml
- filename: helcim-customer-api-openapi.yml
  format: yaml
  label: Helcim Customer API
  slug: helcim-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-customer-api-openapi.yml
- filename: helcim-device-api-openapi.yml
  format: yaml
  label: Helcim Device API
  slug: helcim-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-device-api-openapi.yml
- filename: helcim-general-api-openapi.yml
  format: yaml
  label: Helcim General API
  slug: helcim-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-general-api-openapi.yml
- filename: helcim-invoice-api-openapi.yml
  format: yaml
  label: Helcim Invoice API
  slug: helcim-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-invoice-api-openapi.yml
- filename: helcim-payment-api-openapi.yml
  format: yaml
  label: Helcim Payment API
  slug: helcim-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-payment-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: Helcim Merchant Terms of Service Canada; Tax Configuration covers jurisdictions in Canada and the United States.
  entity_types:
  - text: The Services are available for use only by eligible and permitted businesses, sole proprietors, charities or other entities or persons with legal and legitimate commercial enterprises or endeavors.
    type: business
  minimum_age:
    text: you must be at least the age of majority in the jurisdiction where you reside and the jurisdiction from which you use the Services.
    value: age of majority
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: You may not use the Services for any illegal, fraudulent or unauthorized purpose
  - summary: Household or peer-to-peer transfers
    text: you will not use the Services for household purposes or peer-to-peer money transmission or remittance
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Helcim may reject your application for an Account, or cancel an existing Account, for any reason, in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Helcim
provenance_date: '2026-11-09'
provider_name: Helcim
provider_slug: helcim
slug: helcim-eligibility
source_date: '2026-11-09'
source_filename: helcim-eligibility.yml
source_heading: Eligibility
source_page: https://legal.helcim.com/ca/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Helcim\naid: helcim\nurl: https://legal.helcim.com/ca/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: Helcim Merchant Terms of Service Canada; Tax Configuration covers jurisdictions in Canada and the United\n    States.\nentity_types:\n- type: business\n  text: The Services are available for use only by eligible and permitted businesses, sole proprietors, charities\n    or other entities or persons with legal and legitimate commercial enterprises or endeavors.\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: You may\
  \ not use the Services for any illegal, fraudulent or unauthorized purpose\n- summary: Household or peer-to-peer transfers\n  text: you will not use the Services for household purposes or peer-to-peer money transmission or remittance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Helcim may reject your application for an Account, or cancel an existing Account, for any reason, in its\n    sole discretion.\nminimum_age:\n  value: age of majority\n  text: you must be at least the age of majority in the jurisdiction where you reside and the jurisdiction from\n    which you use the Services.\n"
source_yaml_url: https://artifacts.apis.io/helcim/eligibility/helcim-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Helcim's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Canada
- Payment Gateway
- Payment Processing
- Acquiring
- Merchant Services
- ACH
- Invoicing
- Payment Terminals
- Small Business
---
