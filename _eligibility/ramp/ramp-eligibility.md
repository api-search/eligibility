---
api_specs:
- filename: ramp-accounts-api-openapi.yml
  format: yaml
  label: Ramp Accounts API
  slug: ramp-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-accounts-api-openapi.yml
- filename: ramp-audit-logs-api-openapi.yml
  format: yaml
  label: Ramp Audit Logs API
  slug: ramp-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-audit-logs-api-openapi.yml
- filename: ramp-bills-api-openapi.yml
  format: yaml
  label: Ramp Bills API
  slug: ramp-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-bills-api-openapi.yml
- filename: ramp-cards-api-openapi.yml
  format: yaml
  label: Ramp Cards API
  slug: ramp-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-cards-api-openapi.yml
- filename: ramp-departments-api-openapi.yml
  format: yaml
  label: Ramp Departments API
  slug: ramp-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-departments-api-openapi.yml
- filename: ramp-locations-api-openapi.yml
  format: yaml
  label: Ramp Locations API
  slug: ramp-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-locations-api-openapi.yml
- filename: ramp-reimbursements-api-openapi.yml
  format: yaml
  label: Ramp Reimbursements API
  slug: ramp-reimbursements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-reimbursements-api-openapi.yml
- filename: ramp-statements-api-openapi.yml
  format: yaml
  label: Ramp Statements API
  slug: ramp-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-statements-api-openapi.yml
- filename: ramp-transactions-api-openapi.yml
  format: yaml
  label: Ramp Transactions API
  slug: ramp-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-transactions-api-openapi.yml
- filename: ramp-users-api-openapi.yml
  format: yaml
  label: Ramp Users API
  slug: ramp-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-users-api-openapi.yml
- filename: ramp-vendors-api-openapi.yml
  format: yaml
  label: Ramp Vendors API
  slug: ramp-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ramp/openapi/ramp-vendors-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Only United States Entities and those based in other jurisdictions approved by Ramp may apply for and use a Ramp Account.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No consumer purposes
    text: the Ramp Account may not be used for consumer purposes
  - summary: No sanctioned-party use
    text: provide, provide access to, or use for the benefit of an individual, organization, or country that is blocked or sanctioned under sanctions or export control laws
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
name: Ramp
provenance_date: '2026-11-10'
provider_name: Ramp
provider_slug: ramp
slug: ramp-eligibility
source_date: '2026-11-10'
source_filename: ramp-eligibility.yml
source_heading: Eligibility
source_page: https://ramp.com/legal/customer-terms/platform-agreement/platform-agreement#11-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ramp\naid: ramp\nurl: https://ramp.com/legal/customer-terms/platform-agreement/platform-agreement#11-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Only United States Entities and those based in other jurisdictions approved by Ramp may apply for and use\n    a Ramp Account.\nentity_types: []\nrestricted_uses:\n- summary: No consumer purposes\n  text: the Ramp Account may not be used for consumer purposes\n- summary: No sanctioned-party use\n  text: provide, provide access to, or use for the benefit of an individual, organization, or country that\
  \ is blocked\n    or sanctioned under sanctions or export control laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ramp/eligibility/ramp-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Ramp's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Spend Management
- Corporate Cards
- Expense Management
- Accounts Payable
- Bill Pay
- Accounting
- Reimbursement
---
