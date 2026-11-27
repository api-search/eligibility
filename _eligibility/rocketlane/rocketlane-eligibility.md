---
api_specs:
- filename: rocketlane-comments-api-openapi.yml
  format: yaml
  label: Rocketlane Comments API
  slug: rocketlane-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-comments-api-openapi.yml
- filename: rocketlane-conversations-api-openapi.yml
  format: yaml
  label: Rocketlane Conversations API
  slug: rocketlane-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-conversations-api-openapi.yml
- filename: rocketlane-fields-api-openapi.yml
  format: yaml
  label: Rocketlane Fields API
  slug: rocketlane-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-fields-api-openapi.yml
- filename: rocketlane-invoices-api-openapi.yml
  format: yaml
  label: Rocketlane Invoices API
  slug: rocketlane-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-invoices-api-openapi.yml
- filename: rocketlane-phases-api-openapi.yml
  format: yaml
  label: Rocketlane Phases API
  slug: rocketlane-phases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-phases-api-openapi.yml
- filename: rocketlane-projects-api-openapi.yml
  format: yaml
  label: Rocketlane Projects API
  slug: rocketlane-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-projects-api-openapi.yml
- filename: rocketlane-resource-allocations-api-openapi.yml
  format: yaml
  label: Rocketlane Resource Allocations API
  slug: rocketlane-resource-allocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-resource-allocations-api-openapi.yml
- filename: rocketlane-space-documents-api-openapi.yml
  format: yaml
  label: Rocketlane Space Documents API
  slug: rocketlane-space-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-space-documents-api-openapi.yml
- filename: rocketlane-spaces-api-openapi.yml
  format: yaml
  label: Rocketlane Spaces API
  slug: rocketlane-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-spaces-api-openapi.yml
- filename: rocketlane-tasks-api-openapi.yml
  format: yaml
  label: Rocketlane Tasks API
  slug: rocketlane-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-tasks-api-openapi.yml
- filename: rocketlane-time-offs-api-openapi.yml
  format: yaml
  label: Rocketlane Time-Offs API
  slug: rocketlane-time-offs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-time-offs-api-openapi.yml
- filename: rocketlane-time-tracking-api-openapi.yml
  format: yaml
  label: Rocketlane Time Tracking API
  slug: rocketlane-time-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-time-tracking-api-openapi.yml
- filename: rocketlane-users-api-openapi.yml
  format: yaml
  label: Rocketlane Users API
  slug: rocketlane-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketlane/openapi/rocketlane-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.
    type: individual
  minimum_age:
    text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: No sensitive personal information
    text: You shall not disclose (and shall not permit any individual to disclose) any Sensitive Personal Information to Us for Processing.
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
name: Rocketlane
provenance_date: '2026-11-10'
provider_name: Rocketlane
provider_slug: rocketlane
slug: rocketlane-eligibility
source_date: '2026-11-10'
source_filename: rocketlane-eligibility.yml
source_heading: Eligibility
source_page: https://www.rocketlane.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rocketlane\naid: rocketlane\nurl: https://www.rocketlane.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.\nrestricted_uses:\n- summary: No sensitive personal information\n  text: You shall not disclose (and shall not permit any individual to disclose) any Sensitive Personal Information\n    to Us for Processing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/rocketlane/eligibility/rocketlane-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rocketlane's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Professional Services Automation
- Project Management
- Customer Onboarding
- Resource Management
- Time Tracking
- PSA
- Software-as-a-Service
---
