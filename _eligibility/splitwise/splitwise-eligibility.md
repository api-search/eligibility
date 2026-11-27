---
api_specs:
- filename: splitwise-comments-api-openapi.yml
  format: yaml
  label: Splitwise Comments API
  slug: splitwise-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitwise/openapi/splitwise-comments-api-openapi.yml
- filename: splitwise-expenses-api-openapi.yml
  format: yaml
  label: Splitwise Expenses API
  slug: splitwise-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitwise/openapi/splitwise-expenses-api-openapi.yml
- filename: splitwise-friends-api-openapi.yml
  format: yaml
  label: Splitwise Friends API
  slug: splitwise-friends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitwise/openapi/splitwise-friends-api-openapi.yml
- filename: splitwise-groups-api-openapi.yml
  format: yaml
  label: Splitwise Groups API
  slug: splitwise-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitwise/openapi/splitwise-groups-api-openapi.yml
- filename: splitwise-notifications-api-openapi.yml
  format: yaml
  label: Splitwise Notifications API
  slug: splitwise-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitwise/openapi/splitwise-notifications-api-openapi.yml
- filename: splitwise-other-api-openapi.yml
  format: yaml
  label: Splitwise Other API
  slug: splitwise-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitwise/openapi/splitwise-other-api-openapi.yml
- filename: splitwise-users-api-openapi.yml
  format: yaml
  label: Splitwise Users API
  slug: splitwise-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitwise/openapi/splitwise-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You will only send $USD to other US residents
  entity_types:
  - text: You must be 13 years or older to use this service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: PayPal features limited to US residents
    text: You agree that you will only use these features if you are a US resident, using PayPal with other US residents.
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
name: Splitwise
provenance_date: '2026-11-10'
provider_name: Splitwise
provider_slug: splitwise
slug: splitwise-eligibility
source_date: '2026-11-10'
source_filename: splitwise-eligibility.yml
source_heading: Eligibility
source_page: https://www.splitwise.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Splitwise\naid: splitwise\nurl: https://www.splitwise.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You will only send $USD to other US residents\nentity_types:\n- type: individual\n  text: You must be 13 years or older to use this service.\nrestricted_uses:\n- summary: PayPal features limited to US residents\n  text: You agree that you will only use these features if you are a US resident, using PayPal with other US residents.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/splitwise/eligibility/splitwise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Splitwise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Expense Management
- Personal Finance
- Bill Splitting
- Payments
- REST API
- OAuth
- Authentication
---
