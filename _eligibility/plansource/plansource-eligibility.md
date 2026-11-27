---
api_specs:
- filename: plansource-aca-api-openapi.yml
  format: yaml
  label: PlanSource ACA API
  slug: plansource-aca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-aca-api-openapi.yml
- filename: plansource-administrators-api-openapi.yml
  format: yaml
  label: PlanSource Administrators API
  slug: plansource-administrators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-administrators-api-openapi.yml
- filename: plansource-collections-api-openapi.yml
  format: yaml
  label: PlanSource Collections API
  slug: plansource-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-collections-api-openapi.yml
- filename: plansource-coverage-api-openapi.yml
  format: yaml
  label: PlanSource Coverage API
  slug: plansource-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-coverage-api-openapi.yml
- filename: plansource-demographic-api-openapi.yml
  format: yaml
  label: PlanSource Demographic API
  slug: plansource-demographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-demographic-api-openapi.yml
- filename: plansource-eoi-api-openapi.yml
  format: yaml
  label: PlanSource EOI API
  slug: plansource-eoi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-eoi-api-openapi.yml
- filename: plansource-page-content-api-openapi.yml
  format: yaml
  label: PlanSource Page Content API
  slug: plansource-page-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-page-content-api-openapi.yml
- filename: plansource-payroll-api-openapi.yml
  format: yaml
  label: PlanSource Payroll API
  slug: plansource-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-payroll-api-openapi.yml
- filename: plansource-security-api-openapi.yml
  format: yaml
  label: PlanSource Security API
  slug: plansource-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-security-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Subject to these Terms, you may use the Website and its content for your personal, non-commercial purposes.
    type: individual
  - text: use of our products and services under your or your employer’s agreement with PlanSource
    type: business
  minimum_age:
    text: You must be at least sixteen (16) years old to use our Website.
    value: '16'
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
name: PlanSource
provenance_date: '2026-11-10'
provider_name: PlanSource
provider_slug: plansource
slug: plansource-eligibility
source_date: '2026-11-10'
source_filename: plansource-eligibility.yml
source_heading: Eligibility
source_page: https://plansource.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlanSource\naid: plansource\nurl: https://plansource.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Subject to these Terms, you may use the Website and its content for your personal, non-commercial purposes.\n- type: business\n  text: use of our products and services under your or your employer’s agreement with PlanSource\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least sixteen (16) years old to use our\
  \ Website.\n"
source_yaml_url: https://artifacts.apis.io/plansource/eligibility/plansource-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from PlanSource's own page on 2026-11-10.
synthetic: false
tags:
- Employee Benefits
- Benefits Administration
- Insurance
- Human Resources
- Payroll
- Health Insurance
- Enrollment
- HR Technology
- Evidence of Insurability
- ACA Reporting
- Eligibility
- SSO
- Identity Federation
---
