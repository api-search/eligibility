---
api_specs:
- filename: housecall-pro-companies-api-openapi.yml
  format: yaml
  label: Housecall Pro Companies API
  slug: housecall-pro-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-companies-api-openapi.yml
- filename: housecall-pro-customers-api-openapi.yml
  format: yaml
  label: Housecall Pro Customers API
  slug: housecall-pro-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-customers-api-openapi.yml
- filename: housecall-pro-employees-api-openapi.yml
  format: yaml
  label: Housecall Pro Employees API
  slug: housecall-pro-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-employees-api-openapi.yml
- filename: housecall-pro-estimates-api-openapi.yml
  format: yaml
  label: Housecall Pro Estimates API
  slug: housecall-pro-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-estimates-api-openapi.yml
- filename: housecall-pro-invoices-api-openapi.yml
  format: yaml
  label: Housecall Pro Invoices API
  slug: housecall-pro-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-invoices-api-openapi.yml
- filename: housecall-pro-jobs-api-openapi.yml
  format: yaml
  label: Housecall Pro Jobs API
  slug: housecall-pro-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-jobs-api-openapi.yml
- filename: housecall-pro-leads-api-openapi.yml
  format: yaml
  label: Housecall Pro Leads API
  slug: housecall-pro-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-leads-api-openapi.yml
- filename: housecall-pro-line-items-api-openapi.yml
  format: yaml
  label: Housecall Pro Line Items API
  slug: housecall-pro-line-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-line-items-api-openapi.yml
- filename: housecall-pro-payments-api-openapi.yml
  format: yaml
  label: Housecall Pro Payments API
  slug: housecall-pro-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-payments-api-openapi.yml
- filename: housecall-pro-schedule-items-api-openapi.yml
  format: yaml
  label: Housecall Pro Schedule Items API
  slug: housecall-pro-schedule-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-schedule-items-api-openapi.yml
- filename: housecall-pro-webhooks-api-openapi.yml
  format: yaml
  label: Housecall Pro Webhooks API
  slug: housecall-pro-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housecall-pro/openapi/housecall-pro-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Service is offered to Users who are 18 years of age or older and reside in the United States or Canada.
  minimum_age:
    text: The Service is offered to Users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Payments for unrelated activities
    text: You may not use Housecall Pro Payments for activities unrelated to the activities described in your Business Profile. Without limiting the generality of the foregoing, you may not use Housecall Pro Payments for shipping products, for selling products not related to on-site work
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
name: Housecall Pro
provenance_date: '2026-11-09'
provider_name: Housecall Pro
provider_slug: housecall-pro
slug: housecall-pro-eligibility
source_date: '2026-11-09'
source_filename: housecall-pro-eligibility.yml
source_heading: Eligibility
source_page: https://www.housecallpro.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Housecall Pro\naid: housecall-pro\nurl: https://www.housecallpro.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Service is offered to Users who are 18 years of age or older and reside in the United States or Canada.\nentity_types: []\nrestricted_uses:\n- summary: Payments for unrelated activities\n  text: You may not use Housecall Pro Payments for activities unrelated to the activities described in your Business\n    Profile. Without limiting the generality of the foregoing, you may not use Housecall Pro Payments for shipping\n    products,\
  \ for selling products not related to on-site work\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is offered to Users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/housecall-pro/eligibility/housecall-pro-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Housecall Pro's own page on 2026-11-09.
synthetic: false
tags:
- Home Services
- Field Service Management
- Scheduling
- Dispatching
- Invoicing
- Payments
- HVAC
- Plumbing
- Electrical
- Cleaning
- Landscaping
- Pest Control
- Software-as-a-Service
---
