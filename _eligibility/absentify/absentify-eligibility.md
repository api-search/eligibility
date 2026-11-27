---
api_specs:
- filename: absentify-absences-api-openapi.yml
  format: yaml
  label: Absentify Absences API
  slug: absentify-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-absences-api-openapi.yml
- filename: absentify-departments-api-openapi.yml
  format: yaml
  label: Absentify Departments API
  slug: absentify-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-departments-api-openapi.yml
- filename: absentify-leave-types-api-openapi.yml
  format: yaml
  label: Absentify Leave types API
  slug: absentify-leave-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-leave-types-api-openapi.yml
- filename: absentify-members-api-openapi.yml
  format: yaml
  label: Absentify Members API
  slug: absentify-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-members-api-openapi.yml
- filename: absentify-public-holidays-api-openapi.yml
  format: yaml
  label: Absentify Public holidays API
  slug: absentify-public-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-public-holidays-api-openapi.yml
- filename: absentify-requests-api-openapi.yml
  format: yaml
  label: Absentify Requests API
  slug: absentify-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-requests-api-openapi.yml
- filename: absentify-workspace-api-openapi.yml
  format: yaml
  label: Absentify Workspace API
  slug: absentify-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-workspace-api-openapi.yml
- filename: absentify-allowance-management-api-openapi.yml
  format: yaml
  label: Absentify Allowance Management API
  slug: absentify-allowance-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-allowance-management-api-openapi.yml
- filename: absentify-exports-api-openapi.yml
  format: yaml
  label: Absentify Exports API
  slug: absentify-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-exports-api-openapi.yml
- filename: absentify-out-of-office-api-openapi.yml
  format: yaml
  label: Absentify Out of office API
  slug: absentify-out-of-office-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-out-of-office-api-openapi.yml
- filename: absentify-overtime-api-openapi.yml
  format: yaml
  label: Absentify Overtime API
  slug: absentify-overtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-overtime-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business use.
    type: business
  minimum_age:
    text: You must be at least 16 years of age to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose or in violation of any applicable laws or regulations.
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
name: Absentify
provenance_date: '2026-11-09'
provider_name: Absentify
provider_slug: absentify
slug: absentify-eligibility
source_date: '2026-11-09'
source_filename: absentify-eligibility.yml
source_heading: Eligibility
source_page: https://absentify.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Absentify\naid: absentify\nurl: https://absentify.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for business use.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose or in violation of any applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/absentify/eligibility/absentify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Absentify's own page on 2026-11-09.
synthetic: false
tags:
- Absence Management
- Human Resources
- Leave Management
- Microsoft Teams
---
