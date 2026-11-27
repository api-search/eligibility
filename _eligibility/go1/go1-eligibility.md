---
api_specs:
- filename: go1-enrollments-api-openapi.yml
  format: yaml
  label: Go1 Enrollments API
  slug: go1-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-enrollments-api-openapi.yml
- filename: go1-learning-objects-api-openapi.yml
  format: yaml
  label: Go1 Learning objects API
  slug: go1-learning-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-learning-objects-api-openapi.yml
- filename: go1-portals-api-openapi.yml
  format: yaml
  label: Go1 Portals API
  slug: go1-portals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-portals-api-openapi.yml
- filename: go1-webhooks-api-openapi.yml
  format: yaml
  label: Go1 Webhooks API
  slug: go1-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You must not permit access to or use of the Services in any country or region subject to embargo, sanctions, or other legal restrictions under applicable law or as otherwise notified by Go1 (including, without limitation, Cuba, Iran, North Korea, Syria, and the Crimea/Donetsk/Luhansk regions)
  entity_types:
  - text: Such access and use is permitted solely for your internal business purposes and for the education or training of you or your End Users through the Services
    type: business
  - text: By using the Services, you agree that you are the legal age to form a binding contract
    type: individual
  minimum_age:
    text: you are the legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: No sensitive personal information
    text: You agree not to supply Go1 (either directly or through the Services) with any Sensitive Personal Information.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Upon our request, you will provide the necessary financial documents to allow us to ascertain your creditworthiness.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Go1
provenance_date: '2026-11-09'
provider_name: Go1
provider_slug: go1
slug: go1-eligibility
source_date: '2026-11-09'
source_filename: go1-eligibility.yml
source_heading: Eligibility
source_page: https://www.go1.com/terms/customer-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Go1\naid: go1\nurl: https://www.go1.com/terms/customer-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You must not permit access to or use of the Services in any country or region subject to embargo, sanctions,\n    or other legal restrictions under applicable law or as otherwise notified by Go1 (including, without limitation,\n    Cuba, Iran, North Korea, Syria, and the Crimea/Donetsk/Luhansk regions)\nentity_types:\n- type: business\n  text: Such access and use is permitted solely for your internal business purposes and for the education or training\n\
  \    of you or your End Users through the Services\n- type: individual\n  text: By using the Services, you agree that you are the legal age to form a binding contract\nrestricted_uses:\n- summary: No sensitive personal information\n  text: You agree not to supply Go1 (either directly or through the Services) with any Sensitive Personal Information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Upon our request, you will provide the necessary financial documents to allow us to ascertain your creditworthiness.\nminimum_age:\n  value: null\n  text: you are the legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/go1/eligibility/go1-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Go1's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EdTech
- Learning
- E-Learning
- Corporate Training
- Content
- LMS
- Education
- Webhook
---
