---
api_specs:
- filename: thatch-health-deductions-api-openapi.yml
  format: yaml
  label: Thatch Health Deductions API
  slug: thatch-health-deductions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-deductions-api-openapi.yml
- filename: thatch-health-employees-api-openapi.yml
  format: yaml
  label: Thatch Health Employees API
  slug: thatch-health-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-employees-api-openapi.yml
- filename: thatch-health-employer-onboarding-sessions-api-openapi.yml
  format: yaml
  label: Thatch Health Employer onboarding sessions API
  slug: thatch-health-employer-onboarding-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-employer-onboarding-sessions-api-openapi.yml
- filename: thatch-health-employers-api-openapi.yml
  format: yaml
  label: Thatch Health Employers API
  slug: thatch-health-employers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-employers-api-openapi.yml
- filename: thatch-health-enrollments-api-openapi.yml
  format: yaml
  label: Thatch Health Enrollments API
  slug: thatch-health-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-enrollments-api-openapi.yml
- filename: thatch-health-members-api-openapi.yml
  format: yaml
  label: Thatch Health Members API
  slug: thatch-health-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-members-api-openapi.yml
- filename: thatch-health-pay-schedules-api-openapi.yml
  format: yaml
  label: Thatch Health Pay Schedules API
  slug: thatch-health-pay-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-pay-schedules-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to consent to a User Agreement and open an account.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to consent to a User Agreement and open an account.
    value: '18'
  restricted_uses:
  - summary: Use of funds inconsistent with Healthcare Notices
    text: Use of funds not supported by the Healthcare Notices is prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Thatch and its financial partners may request additional information to fulfill their legal requirements and may engage third-party service providers to verify this information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Thatch Health
provenance_date: '2026-11-10'
provider_name: Thatch Health
provider_slug: thatch-health
slug: thatch-health-eligibility
source_date: '2026-11-10'
source_filename: thatch-health-eligibility.yml
source_heading: Eligibility
source_page: https://thatch.com/legal/platform-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thatch Health\naid: thatch-health\nurl: https://thatch.com/legal/platform-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to consent to a User Agreement and open an account.\nrestricted_uses:\n- summary: Use of funds inconsistent with Healthcare Notices\n  text: Use of funds not supported by the Healthcare Notices is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Thatch and its financial partners may request additional information to fulfill their legal\
  \ requirements\n    and may engage third-party service providers to verify this information.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to consent to a User Agreement and open an account.\n"
source_yaml_url: https://artifacts.apis.io/thatch-health/eligibility/thatch-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Thatch Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Benefits
- ICHRA
- Insurance
- Payroll
- Embedded Benefits
- Human Resources
---
