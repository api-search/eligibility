---
api_specs:
- filename: bankday-dev-account-api-openapi.yml
  format: yaml
  label: bankday-dev Account API
  slug: bankday-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-account-api-openapi.yml
- filename: bankday-dev-ach-api-openapi.yml
  format: yaml
  label: bankday-dev Ach API
  slug: bankday-dev-ach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-ach-api-openapi.yml
- filename: bankday-dev-business-day-api-openapi.yml
  format: yaml
  label: bankday-dev Business Day API
  slug: bankday-dev-business-day-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-business-day-api-openapi.yml
- filename: bankday-dev-business-days-api-openapi.yml
  format: yaml
  label: bankday-dev Business Days API
  slug: bankday-dev-business-days-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-business-days-api-openapi.yml
- filename: bankday-dev-calendars-api-openapi.yml
  format: yaml
  label: bankday-dev Calendars API
  slug: bankday-dev-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-calendars-api-openapi.yml
- filename: bankday-dev-fx-api-openapi.yml
  format: yaml
  label: bankday-dev Fx API
  slug: bankday-dev-fx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-fx-api-openapi.yml
- filename: bankday-dev-holidays-api-openapi.yml
  format: yaml
  label: bankday-dev Holidays API
  slug: bankday-dev-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-holidays-api-openapi.yml
- filename: bankday-dev-minimum-wage-api-openapi.yml
  format: yaml
  label: bankday-dev Minimum Wage API
  slug: bankday-dev-minimum-wage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-minimum-wage-api-openapi.yml
- filename: bankday-dev-payroll-api-openapi.yml
  format: yaml
  label: bankday-dev Payroll API
  slug: bankday-dev-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-payroll-api-openapi.yml
- filename: bankday-dev-today-api-openapi.yml
  format: yaml
  label: bankday-dev Today API
  slug: bankday-dev-today-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-today-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One free account per person or organisation
    type: individual
  - text: One free account per person or organisation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Resale as competing data feed
    text: Do not resell raw access to the API as a competing data feed
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
name: bankday-dev
provenance_date: '2026-11-09'
provider_name: bankday-dev
provider_slug: bankday-dev
slug: bankday-dev-eligibility
source_date: '2026-11-09'
source_filename: bankday-dev-eligibility.yml
source_heading: Eligibility
source_page: https://bankday.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bankday-dev\naid: bankday-dev\nurl: https://bankday.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One free account per person or organisation\n- type: business\n  text: One free account per person or organisation\nrestricted_uses:\n- summary: Resale as competing data feed\n  text: Do not resell raw access to the API as a competing data feed\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bankday-dev/eligibility/bankday-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from bankday-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Calendar
- Payments
---
