---
api_specs:
- filename: dispatch-appointments-api-openapi.yml
  format: yaml
  label: Dispatch Appointments API
  slug: dispatch-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-appointments-api-openapi.yml
- filename: dispatch-authentication-api-openapi.yml
  format: yaml
  label: Dispatch Authentication API
  slug: dispatch-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-authentication-api-openapi.yml
- filename: dispatch-brands-api-openapi.yml
  format: yaml
  label: Dispatch Brands API
  slug: dispatch-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-brands-api-openapi.yml
- filename: dispatch-customers-api-openapi.yml
  format: yaml
  label: Dispatch Customers API
  slug: dispatch-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-customers-api-openapi.yml
- filename: dispatch-files-api-openapi.yml
  format: yaml
  label: Dispatch Files API
  slug: dispatch-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-files-api-openapi.yml
- filename: dispatch-jobs-api-openapi.yml
  format: yaml
  label: Dispatch Jobs API
  slug: dispatch-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-jobs-api-openapi.yml
- filename: dispatch-organizations-api-openapi.yml
  format: yaml
  label: Dispatch Organizations API
  slug: dispatch-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-organizations-api-openapi.yml
- filename: dispatch-sources-api-openapi.yml
  format: yaml
  label: Dispatch Sources API
  slug: dispatch-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-sources-api-openapi.yml
- filename: dispatch-survey-responses-api-openapi.yml
  format: yaml
  label: Dispatch Survey Responses API
  slug: dispatch-survey-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-survey-responses-api-openapi.yml
- filename: dispatch-users-api-openapi.yml
  format: yaml
  label: Dispatch Users API
  slug: dispatch-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-users-api-openapi.yml
- filename: dispatch-work-orders-api-openapi.yml
  format: yaml
  label: Dispatch Work Orders API
  slug: dispatch-work-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dispatch/openapi/dispatch-work-orders-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation or warranty that all of the features of Dispatch Services will be available to you outside of the United States
  entity_types:
  - text: you are at least eighteen (18) years old
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: You will not use Dispatch Services for high risk activities such as the operation of nuclear facilities, air traffic control, or life support systems
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We have the final discretion in granting accounts, and reserve the right to reject your registration without explanation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dispatch
provenance_date: '2026-11-09'
provider_name: Dispatch
provider_slug: dispatch
slug: dispatch-eligibility
source_date: '2026-11-09'
source_filename: dispatch-eligibility.yml
source_heading: Eligibility
source_page: https://dispatch.me/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dispatch\naid: dispatch\nurl: https://dispatch.me/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation or warranty that all of the features of Dispatch Services will be available to\n    you outside of the United States\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years old\nrestricted_uses:\n- summary: High-risk activities\n  text: You will not use Dispatch Services for high risk activities such as the operation of nuclear facilities,\n    air traffic control, or life support systems\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: We have the final discretion in granting accounts, and reserve the right to reject your registration without\n    explanation.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/dispatch/eligibility/dispatch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Dispatch's own page on 2026-11-09.
synthetic: false
tags:
- Field Service Management
- Service Orchestration
- Work Orders
- Scheduling
- Contractor Networks
- Home Services
- Warranty
- Customer Experience
- Logistics
- Company
---
