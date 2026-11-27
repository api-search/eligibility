---
api_specs:
- filename: weel-accounting-codes-api-openapi.yml
  format: yaml
  label: Weel Accounting Codes API
  slug: weel-accounting-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-accounting-codes-api-openapi.yml
- filename: weel-budget-members-api-openapi.yml
  format: yaml
  label: Weel Budget Members API
  slug: weel-budget-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-budget-members-api-openapi.yml
- filename: weel-budget-owners-api-openapi.yml
  format: yaml
  label: Weel Budget Owners API
  slug: weel-budget-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-budget-owners-api-openapi.yml
- filename: weel-budget-topups-api-openapi.yml
  format: yaml
  label: Weel Budget Topups API
  slug: weel-budget-topups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-budget-topups-api-openapi.yml
- filename: weel-budgets-api-openapi.yml
  format: yaml
  label: Weel Budgets API
  slug: weel-budgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-budgets-api-openapi.yml
- filename: weel-categories-api-openapi.yml
  format: yaml
  label: Weel Categories API
  slug: weel-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-categories-api-openapi.yml
- filename: weel-custom-field-budgets-api-openapi.yml
  format: yaml
  label: Weel Custom Field Budgets API
  slug: weel-custom-field-budgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-custom-field-budgets-api-openapi.yml
- filename: weel-custom-field-options-api-openapi.yml
  format: yaml
  label: Weel Custom Field Options API
  slug: weel-custom-field-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-custom-field-options-api-openapi.yml
- filename: weel-custom-fields-api-openapi.yml
  format: yaml
  label: Weel Custom Fields API
  slug: weel-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-custom-fields-api-openapi.yml
- filename: weel-invites-api-openapi.yml
  format: yaml
  label: Weel Invites API
  slug: weel-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-invites-api-openapi.yml
- filename: weel-roles-api-openapi.yml
  format: yaml
  label: Weel Roles API
  slug: weel-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-roles-api-openapi.yml
- filename: weel-statements-api-openapi.yml
  format: yaml
  label: Weel Statements API
  slug: weel-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-statements-api-openapi.yml
- filename: weel-tax-rates-api-openapi.yml
  format: yaml
  label: Weel Tax Rates API
  slug: weel-tax-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-tax-rates-api-openapi.yml
- filename: weel-transactions-api-openapi.yml
  format: yaml
  label: Weel Transactions API
  slug: weel-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-transactions-api-openapi.yml
- filename: weel-users-api-openapi.yml
  format: yaml
  label: Weel Users API
  slug: weel-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weel/openapi/weel-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - NZ
    text: 'Australia: Financial services are provided by Nium Pty Limited ACN 601 384 025 (AFS licence 464627). New Zealand: Financial services are provided by Nium (New Zealand) Limited NZCN 9076652 (FSP 1006810) and Weel New Zealand Limited NZCN 9295557 (FSP 1009961).'
  minimum_age:
    text: null
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
name: Weel
provenance_date: '2026-11-10'
provider_name: Weel
provider_slug: weel
slug: weel-eligibility
source_date: '2026-11-10'
source_filename: weel-eligibility.yml
source_heading: Eligibility
source_page: https://letsweel.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Weel\naid: weel\nurl: https://letsweel.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - NZ\n  excluded: []\n  text: 'Australia: Financial services are provided by Nium Pty Limited ACN 601 384 025 (AFS licence 464627). New\n    Zealand: Financial services are provided by Nium (New Zealand) Limited NZCN 9076652 (FSP 1006810) and Weel New\n    Zealand Limited NZCN 9295557 (FSP 1009961).'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/weel/eligibility/weel-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Weel's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Australia
- Spend Management
- Expense Management
- Corporate Cards
- Accounts Payable
- Card Issuing
- Reimbursement
- Budgets
- Fintech
---
