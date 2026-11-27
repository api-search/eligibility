---
api_specs:
- filename: gusto-asyncapi.yml
  format: yaml
  label: Gusto Embedded Payroll API
  slug: embedded-payroll-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-asyncapi.yml
- filename: gusto-companies-api-openapi.yml
  format: yaml
  label: Gusto Companies API
  slug: gusto-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-companies-api-openapi.yml
- filename: gusto-contractors-api-openapi.yml
  format: yaml
  label: Gusto Contractors API
  slug: gusto-contractors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-contractors-api-openapi.yml
- filename: gusto-employees-api-openapi.yml
  format: yaml
  label: Gusto Employees API
  slug: gusto-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-employees-api-openapi.yml
- filename: gusto-flows-api-openapi.yml
  format: yaml
  label: Gusto Flows API
  slug: gusto-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-flows-api-openapi.yml
- filename: gusto-payrolls-api-openapi.yml
  format: yaml
  label: Gusto Payrolls API
  slug: gusto-payrolls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-payrolls-api-openapi.yml
- filename: gusto-reports-api-openapi.yml
  format: yaml
  label: Gusto Reports API
  slug: gusto-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-reports-api-openapi.yml
- filename: gusto-webhooks-api-openapi.yml
  format: yaml
  label: Gusto Webhooks API
  slug: gusto-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-webhooks-api-openapi.yml
- filename: gusto-bank-accounts-api-openapi.yml
  format: yaml
  label: Gusto Bank Accounts API
  slug: gusto-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-bank-accounts-api-openapi.yml
- filename: gusto-contractor-payments-api-openapi.yml
  format: yaml
  label: Gusto Contractor Payments API
  slug: gusto-contractor-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-contractor-payments-api-openapi.yml
- filename: gusto-pay-schedules-api-openapi.yml
  format: yaml
  label: Gusto Pay Schedules API
  slug: gusto-pay-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-pay-schedules-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Bank Account must be in the United States.
  entity_types:
  - text: If you are an accountant or bookkeeper using Gusto Pro and/or are managing your client’s or customer’s use of the Platform or Services, this Agreement and the Gusto Accountant Terms of Service govern your access
    type: other
  minimum_age:
    text: You must be at least 18 years old to create an Employer Account.
    value: '18'
  restricted_uses:
  - summary: High-risk business activities
    text: Gusto may limit access to Services or Service Plans for Employers who engage in certain high risk business activities (as determined by Gusto).
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Gusto's account opening and maintenance processes include controls designed to gather information required under the Bank Secrecy Act
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gusto
provenance_date: '2026-11-09'
provider_name: Gusto
provider_slug: gusto
slug: gusto-eligibility
source_date: '2026-11-09'
source_filename: gusto-eligibility.yml
source_heading: Eligibility
source_page: https://gusto.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gusto\naid: gusto\nurl: https://gusto.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Bank Account must be in the United States.\nentity_types:\n- type: other\n  text: If you are an accountant or bookkeeper using Gusto Pro and/or are managing your client’s or customer’s use\n    of the Platform or Services, this Agreement and the Gusto Accountant Terms of Service govern your access\nrestricted_uses:\n- summary: High-risk business activities\n  text: Gusto may limit access to Services or Service Plans for Employers who engage in certain high\
  \ risk business\n    activities (as determined by Gusto).\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Gusto's account opening and maintenance processes include controls designed to gather information required\n    under the Bank Secrecy Act\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an Employer Account.\n"
source_yaml_url: https://artifacts.apis.io/gusto/eligibility/gusto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Gusto's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Payroll
- Benefits
- Enterprise Software
- Embedded Finance
- Employee Benefits
---
