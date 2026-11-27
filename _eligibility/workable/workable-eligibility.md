---
api_specs:
- filename: workable-accounts-api-openapi.yml
  format: yaml
  label: Workable Accounts API
  slug: workable-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-accounts-api-openapi.yml
- filename: workable-candidates-api-openapi.yml
  format: yaml
  label: Workable Candidates API
  slug: workable-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-candidates-api-openapi.yml
- filename: workable-departments-api-openapi.yml
  format: yaml
  label: Workable Departments API
  slug: workable-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-departments-api-openapi.yml
- filename: workable-employees-api-openapi.yml
  format: yaml
  label: Workable Employees API
  slug: workable-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-employees-api-openapi.yml
- filename: workable-events-api-openapi.yml
  format: yaml
  label: Workable Events API
  slug: workable-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-events-api-openapi.yml
- filename: workable-jobs-api-openapi.yml
  format: yaml
  label: Workable Jobs API
  slug: workable-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-jobs-api-openapi.yml
- filename: workable-members-api-openapi.yml
  format: yaml
  label: Workable Members API
  slug: workable-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-members-api-openapi.yml
- filename: workable-offers-api-openapi.yml
  format: yaml
  label: Workable Offers API
  slug: workable-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-offers-api-openapi.yml
- filename: workable-recruiters-api-openapi.yml
  format: yaml
  label: Workable Recruiters API
  slug: workable-recruiters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-recruiters-api-openapi.yml
- filename: workable-requisitions-api-openapi.yml
  format: yaml
  label: Workable Requisitions API
  slug: workable-requisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-requisitions-api-openapi.yml
- filename: workable-stages-api-openapi.yml
  format: yaml
  label: Workable Stages API
  slug: workable-stages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-stages-api-openapi.yml
- filename: workable-subscriptions-api-openapi.yml
  format: yaml
  label: Workable Subscriptions API
  slug: workable-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-subscriptions-api-openapi.yml
- filename: workable-custom-attributes-api-openapi.yml
  format: yaml
  label: Workable Custom Attributes API
  slug: workable-custom-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-custom-attributes-api-openapi.yml
- filename: workable-review-cycles-api-openapi.yml
  format: yaml
  label: Workable Review Cycles API
  slug: workable-review-cycles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-review-cycles-api-openapi.yml
- filename: workable-time-off-api-openapi.yml
  format: yaml
  label: Workable Time Off API
  slug: workable-time-off-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-time-off-api-openapi.yml
- filename: workable-time-tracking-api-openapi.yml
  format: yaml
  label: Workable Time Tracking API
  slug: workable-time-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-time-tracking-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Pricing may vary by billing country. No country served or excluded list is stated.
  entity_types:
  - text: You acknowledge and agree that by signing up online to use the Services, or by executing an Order Form, on behalf of a nominated company or organisation (" Customer "), you agree that the company or organisation will be bound by these terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Protected health information
    text: Customer acknowledges and agrees that it will not upload or store to the Services any protected health information regulated by the Health Insurance Portability and Accountability Act (“ HIPAA ”), or any other similar laws, as applicable.
  - summary: Recruitment content restrictions
    text: Customer shall ensure that the Services are not used to (a) post false, misleading, or non-existent Openings, (b) post multi-level marketing or similar schemes, (c) harvest Candidates for improper purposes
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
name: Workable
provenance_date: '2026-11-10'
provider_name: Workable
provider_slug: workable
slug: workable-eligibility
source_date: '2026-11-10'
source_filename: workable-eligibility.yml
source_heading: Eligibility
source_page: https://www.workable.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workable\naid: workable\nurl: https://www.workable.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Pricing may vary by billing country. No country served or excluded list is stated.\nentity_types:\n- type: business\n  text: You acknowledge and agree that by signing up online to use the Services, or by executing an Order Form,\n    on behalf of a nominated company or organisation (\" Customer \"), you agree that the company or organisation\n    will be bound by these terms.\nrestricted_uses:\n- summary: Protected health information\n  text: Customer acknowledges and agrees\
  \ that it will not upload or store to the Services any protected health information\n    regulated by the Health Insurance Portability and Accountability Act (“ HIPAA ”), or any other similar laws,\n    as applicable.\n- summary: Recruitment content restrictions\n  text: Customer shall ensure that the Services are not used to (a) post false, misleading, or non-existent Openings,\n    (b) post multi-level marketing or similar schemes, (c) harvest Candidates for improper purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workable/eligibility/workable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Workable's own page on 2026-11-10.
synthetic: false
tags:
- Human Resources
- Applicant Tracking
- Recruiting
- Sourcing
- Video Interviews
- Assessment
- Software-as-a-Service
---
