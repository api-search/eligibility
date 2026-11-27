---
api_specs:
- filename: wagestream-absences-api-openapi.yml
  format: yaml
  label: Wagestream Absences API
  slug: wagestream-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-absences-api-openapi.yml
- filename: wagestream-employees-api-openapi.yml
  format: yaml
  label: Wagestream Employees API
  slug: wagestream-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-employees-api-openapi.yml
- filename: wagestream-enrollment-api-openapi.yml
  format: yaml
  label: Wagestream Enrollment API
  slug: wagestream-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-enrollment-api-openapi.yml
- filename: wagestream-off-cycle-payment-api-openapi.yml
  format: yaml
  label: Wagestream Off Cycle Payment API
  slug: wagestream-off-cycle-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-off-cycle-payment-api-openapi.yml
- filename: wagestream-shifts-api-openapi.yml
  format: yaml
  label: Wagestream Shifts API
  slug: wagestream-shifts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-shifts-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are a business user: We will not be liable to you for any loss or damage'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use by consumers
    text: You agree not to use our site for any commercial or business purposes
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
name: Wagestream
provenance_date: '2026-11-10'
provider_name: Wagestream
provider_slug: wagestream
slug: wagestream-eligibility
source_date: '2026-11-10'
source_filename: wagestream-eligibility.yml
source_heading: Eligibility
source_page: https://stream.co/en/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wagestream\naid: wagestream\nurl: https://stream.co/en/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are a business user: We will not be liable to you for any loss or damage'\nrestricted_uses:\n- summary: No commercial use by consumers\n  text: You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wagestream/eligibility/wagestream-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Wagestream's own page on 2026-11-10.
synthetic: false
tags:
- Financial Wellbeing
- Earned Wage Access
- Fintech
- Payroll
- Human Resources
- Workforce Management
- Time and Attendance
- Employee Benefits
- Workplace Savings
- HR Integrations
- B Corp
- United Kingdom
---
