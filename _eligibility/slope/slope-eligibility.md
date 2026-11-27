---
api_specs:
- filename: slope-auth-api-openapi.yml
  format: yaml
  label: Slope Auth API
  slug: slope-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-auth-api-openapi.yml
- filename: slope-customers-api-openapi.yml
  format: yaml
  label: Slope Customers API
  slug: slope-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-customers-api-openapi.yml
- filename: slope-files-api-openapi.yml
  format: yaml
  label: Slope Files API
  slug: slope-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-files-api-openapi.yml
- filename: slope-orders-api-openapi.yml
  format: yaml
  label: Slope Orders API
  slug: slope-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-orders-api-openapi.yml
- filename: slope-payout-accounts-api-openapi.yml
  format: yaml
  label: Slope Payout Accounts API
  slug: slope-payout-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-payout-accounts-api-openapi.yml
- filename: slope-persons-api-openapi.yml
  format: yaml
  label: Slope Persons API
  slug: slope-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-persons-api-openapi.yml
- filename: slope-prescreens-api-openapi.yml
  format: yaml
  label: Slope Prescreens API
  slug: slope-prescreens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-prescreens-api-openapi.yml
- filename: slope-simulation-api-openapi.yml
  format: yaml
  label: Slope Simulation API
  slug: slope-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-simulation-api-openapi.yml
- filename: slope-transactions-api-openapi.yml
  format: yaml
  label: Slope Transactions API
  slug: slope-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-transactions-api-openapi.yml
- filename: slope-user-links-api-openapi.yml
  format: yaml
  label: Slope User Links API
  slug: slope-user-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slope/openapi/slope-user-links-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website and Services are offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Website and Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use
    text: These Terms of Use permit you to use the Website for your personal, non-commercial use only.
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
name: Slope
provenance_date: '2026-11-10'
provider_name: Slope
provider_slug: slope
slug: slope-eligibility
source_date: '2026-11-10'
source_filename: slope-eligibility.yml
source_heading: Eligibility
source_page: https://slopepay.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Slope\naid: slope\nurl: https://slopepay.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website and Services are offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Personal non-commercial use\n  text: These Terms of Use permit you to use the Website for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: This Website and Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/slope/eligibility/slope-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Slope's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Embedded Finance
- Buy Now Pay Later
- Lending
- Credit
- B2B
- Checkout
---
