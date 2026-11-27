---
api_specs:
- filename: fifth-third-bancorp-auth-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Auth API
  slug: fifth-third-bancorp-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-auth-api-openapi.yml
- filename: fifth-third-bancorp-combined-transfers-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Combined Transfers API
  slug: fifth-third-bancorp-combined-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-combined-transfers-api-openapi.yml
- filename: fifth-third-bancorp-custodial-accounts-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Custodial Accounts API
  slug: fifth-third-bancorp-custodial-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-custodial-accounts-api-openapi.yml
- filename: fifth-third-bancorp-customer-products-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Customer Products API
  slug: fifth-third-bancorp-customer-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-customer-products-api-openapi.yml
- filename: fifth-third-bancorp-customers-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Customers API
  slug: fifth-third-bancorp-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-customers-api-openapi.yml
- filename: fifth-third-bancorp-pools-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Pools API
  slug: fifth-third-bancorp-pools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-pools-api-openapi.yml
- filename: fifth-third-bancorp-products-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Products API
  slug: fifth-third-bancorp-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-products-api-openapi.yml
- filename: fifth-third-bancorp-returns-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Returns API
  slug: fifth-third-bancorp-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-returns-api-openapi.yml
- filename: fifth-third-bancorp-sandbox-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Sandbox API
  slug: fifth-third-bancorp-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-sandbox-api-openapi.yml
- filename: fifth-third-bancorp-synthetic-accounts-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Synthetic Accounts API
  slug: fifth-third-bancorp-synthetic-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-synthetic-accounts-api-openapi.yml
- filename: fifth-third-bancorp-transactions-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Transactions API
  slug: fifth-third-bancorp-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-transactions-api-openapi.yml
- filename: fifth-third-bancorp-transfers-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Transfers API
  slug: fifth-third-bancorp-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-transfers-api-openapi.yml
- filename: fifth-third-bancorp-virtual-reference-numbers-api-openapi.yml
  format: yaml
  label: Fifth Third Bancorp Virtual Reference Numbers API
  slug: fifth-third-bancorp-virtual-reference-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fifth-third-bancorp/openapi/fifth-third-bancorp-virtual-reference-numbers-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (either an individual or a single business entity) (the “Customer”)
    type: individual
  - text: you (either an individual or a single business entity) (the “Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No nonpublic or personal information
    text: CUSTOMER SHALL NOT INPUT OR OTHERWISE USE NONPUBLIC PERSONAL INFORMATION (NPI) OR PERSONAL INFORMATION (PI) IN OR WITH THE SOFTWARE OR WEBSITE.
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
name: Fifth Third Bancorp
provenance_date: '2026-11-09'
provider_name: Fifth Third Bancorp
provider_slug: fifth-third-bancorp
slug: fifth-third-bancorp-eligibility
source_date: '2026-11-09'
source_filename: fifth-third-bancorp-eligibility.yml
source_heading: Eligibility
source_page: https://developers.newline53.com/docs/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fifth Third Bancorp\naid: fifth-third-bancorp\nurl: https://developers.newline53.com/docs/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (either an individual or a single business entity) (the “Customer”)\n- type: business\n  text: you (either an individual or a single business entity) (the “Customer”)\nrestricted_uses:\n- summary: No nonpublic or personal information\n  text: CUSTOMER SHALL NOT INPUT OR OTHERWISE USE NONPUBLIC PERSONAL INFORMATION (NPI) OR PERSONAL INFORMATION (PI)\n    IN OR WITH THE SOFTWARE\
  \ OR WEBSITE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fifth-third-bancorp/eligibility/fifth-third-bancorp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Fifth Third Bancorp's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- United States
- Embedded Finance
- Banking as a Service
- Payments
- ACH
- Real-Time Payments
- Deposits
- Card Issuing
- Commercial Banking
- Consumer Lending
- Wealth Management
- Treasury Management
- Super-Regional Bank
- Fortune 500
---
