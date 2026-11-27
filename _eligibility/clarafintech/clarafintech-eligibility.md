---
api_specs:
- filename: clarafintech-accounts-payable-api-openapi.yml
  format: yaml
  label: Clarafintech Accounts Payable API
  slug: clarafintech-accounts-payable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-accounts-payable-api-openapi.yml
- filename: clarafintech-authentication-api-openapi.yml
  format: yaml
  label: Clarafintech Authentication API
  slug: clarafintech-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-authentication-api-openapi.yml
- filename: clarafintech-billing-statements-api-openapi.yml
  format: yaml
  label: Clarafintech Billing Statements API
  slug: clarafintech-billing-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-billing-statements-api-openapi.yml
- filename: clarafintech-cards-api-openapi.yml
  format: yaml
  label: Clarafintech Cards API
  slug: clarafintech-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-cards-api-openapi.yml
- filename: clarafintech-digital-account-api-openapi.yml
  format: yaml
  label: Clarafintech Digital Account API
  slug: clarafintech-digital-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-digital-account-api-openapi.yml
- filename: clarafintech-extracted-documents-api-openapi.yml
  format: yaml
  label: Clarafintech Extracted Documents API
  slug: clarafintech-extracted-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-extracted-documents-api-openapi.yml
- filename: clarafintech-invoices-api-openapi.yml
  format: yaml
  label: Clarafintech Invoices API
  slug: clarafintech-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-invoices-api-openapi.yml
- filename: clarafintech-reimbursements-api-openapi.yml
  format: yaml
  label: Clarafintech Reimbursements API
  slug: clarafintech-reimbursements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-reimbursements-api-openapi.yml
- filename: clarafintech-transactions-api-openapi.yml
  format: yaml
  label: Clarafintech Transactions API
  slug: clarafintech-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-transactions-api-openapi.yml
- filename: clarafintech-users-api-openapi.yml
  format: yaml
  label: Clarafintech Users API
  slug: clarafintech-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    - BR
    - CO
    text: Based in Mexico, Brazil, or Colombia? Click here → (local platforms México Colombia Brasil)
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent activity
    text: Clara does not authorize or consent to the use of the Service for unlawful or fraudulent activities or activities contrary to public order.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'The information and documentation provided by the Client will be evaluated by Clara primarily for the following purposes: Identifying the Client and the Administrators; and Complying with the legal and regulatory provisions applicable to Clara.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clarafintech
provenance_date: '2026-11-09'
provider_name: Clarafintech
provider_slug: clarafintech
slug: clarafintech-eligibility
source_date: '2026-11-09'
source_filename: clarafintech-eligibility.yml
source_heading: Eligibility
source_page: https://www.clara.com/global/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clarafintech\naid: clarafintech\nurl: https://www.clara.com/global/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  - BR\n  - CO\n  excluded: []\n  text: Based in Mexico, Brazil, or Colombia? Click here → (local platforms México Colombia Brasil)\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fraudulent activity\n  text: Clara does not authorize or consent to the use of the Service for unlawful or fraudulent activities or activities\n    contrary to public order.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'The information and documentation provided\
  \ by the Client will be evaluated by Clara primarily for the following\n    purposes: Identifying the Client and the Administrators; and Complying with the legal and regulatory provisions\n    applicable to Clara.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clarafintech/eligibility/clarafintech-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Clarafintech's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Spend Management
- Latin America
- Corporate Cards
- Financial Automation
- Company
---
