---
api_specs:
- filename: workstream-applicants-api-openapi.yml
  format: yaml
  label: Workstream Applicants API
  slug: workstream-applicants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-applicants-api-openapi.yml
- filename: workstream-authorization-api-openapi.yml
  format: yaml
  label: Workstream Authorization API
  slug: workstream-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-authorization-api-openapi.yml
- filename: workstream-company-roles-api-openapi.yml
  format: yaml
  label: Workstream Company Roles API
  slug: workstream-company-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-company-roles-api-openapi.yml
- filename: workstream-company-users-api-openapi.yml
  format: yaml
  label: Workstream Company Users API
  slug: workstream-company-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-company-users-api-openapi.yml
- filename: workstream-custom-field-api-openapi.yml
  format: yaml
  label: Workstream Custom Field API
  slug: workstream-custom-field-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-custom-field-api-openapi.yml
- filename: workstream-departments-api-openapi.yml
  format: yaml
  label: Workstream Departments API
  slug: workstream-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-departments-api-openapi.yml
- filename: workstream-employee-documents-api-openapi.yml
  format: yaml
  label: Workstream Employee Documents API
  slug: workstream-employee-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-employee-documents-api-openapi.yml
- filename: workstream-employees-api-openapi.yml
  format: yaml
  label: Workstream Employees API
  slug: workstream-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-employees-api-openapi.yml
- filename: workstream-imported-employee-infos-api-openapi.yml
  format: yaml
  label: Workstream Imported Employee Infos API
  slug: workstream-imported-employee-infos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-imported-employee-infos-api-openapi.yml
- filename: workstream-locations-api-openapi.yml
  format: yaml
  label: Workstream Locations API
  slug: workstream-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-locations-api-openapi.yml
- filename: workstream-positions-api-openapi.yml
  format: yaml
  label: Workstream Positions API
  slug: workstream-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-positions-api-openapi.yml
- filename: workstream-team-members-api-openapi.yml
  format: yaml
  label: Workstream Team Members API
  slug: workstream-team-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workstream/openapi/workstream-team-members-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are not intended for, and should not be used by, anyone under the age of 13, except as expressly permitted by applicable local laws.
    value: '13'
  restricted_uses:
  - summary: Illegal or unlawful use
    text: Customer acknowledges that the Services may only be used for legitimate transactions that are permitted by law.
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
name: Workstream
provenance_date: '2026-11-10'
provider_name: Workstream
provider_slug: workstream
slug: workstream-eligibility
source_date: '2026-11-10'
source_filename: workstream-eligibility.yml
source_heading: Eligibility
source_page: https://www.workstream.us:443/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workstream\naid: workstream\nurl: https://www.workstream.us:443/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: Customer acknowledges that the Services may only be used for legitimate transactions that are permitted\n    by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are not intended for, and should not be used by, anyone under the age of 13, except as expressly\n    permitted\
  \ by applicable local laws.\n"
source_yaml_url: https://artifacts.apis.io/workstream/eligibility/workstream-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Workstream's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Human Resources
- Hiring
- Payroll
- Onboarding
- Applicant Tracking
- Hourly Workforce
- Restaurant
---
