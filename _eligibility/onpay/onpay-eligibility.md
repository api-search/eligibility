---
api_specs:
- filename: onpay-company-api-openapi.yml
  format: yaml
  label: OnPay Company API
  slug: onpay-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-company-api-openapi.yml
- filename: onpay-deductions-api-openapi.yml
  format: yaml
  label: OnPay Deductions API
  slug: onpay-deductions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-deductions-api-openapi.yml
- filename: onpay-employees-api-openapi.yml
  format: yaml
  label: OnPay Employees API
  slug: onpay-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-employees-api-openapi.yml
- filename: onpay-pay-runs-api-openapi.yml
  format: yaml
  label: OnPay Pay Runs API
  slug: onpay-pay-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-pay-runs-api-openapi.yml
- filename: onpay-reports-api-openapi.yml
  format: yaml
  label: OnPay Reports API
  slug: onpay-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-reports-api-openapi.yml
- filename: onpay-user-api-openapi.yml
  format: yaml
  label: OnPay User API
  slug: onpay-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-user-api-openapi.yml
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
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Service Bureau may, at its discretion, decline to offer the Service to Client in the event that the enrollment process is not satisfactorily completed, Service Bureau is unable to verify satisfactory credit of the Client
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OnPay
provenance_date: '2026-11-10'
provider_name: OnPay
provider_slug: onpay
slug: onpay-eligibility
source_date: '2026-11-10'
source_filename: onpay-eligibility.yml
source_heading: Eligibility
source_page: https://onpay.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnPay\naid: onpay\nurl: https://onpay.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Service Bureau may, at its discretion, decline to offer the Service to Client in the event that the enrollment\n    process is not satisfactorily completed, Service Bureau is unable to verify satisfactory credit of the Client\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onpay/eligibility/onpay-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from OnPay's own page on 2026-11-10.
synthetic: false
tags:
- Payroll
- Human Resources
- Employee Benefits
- Payroll Tax
- Small Business
- Workforce Management
- Fintech
- Time and Attendance
- retirement-401k
---
