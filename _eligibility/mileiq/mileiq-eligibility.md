---
api_specs:
- filename: mileiq-groups-api-openapi.yml
  format: yaml
  label: MileIQ Groups API
  slug: mileiq-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mileiq/openapi/mileiq-groups-api-openapi.yml
- filename: mileiq-users-api-openapi.yml
  format: yaml
  label: MileIQ Users API
  slug: mileiq-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mileiq/openapi/mileiq-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some services and features may not be available in all countries, in all languages, or in all operating systems. You represent you are not located in a country subject to a U.S. Government embargo.
  entity_types:
  - text: If you are entering into an agreement with us on behalf of an entity or company, you will need to enter into the Enterprise Customer Terms of Use found below.
    type: business
  minimum_age:
    text: The Services are intended solely for users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Use only when safe to do so
    text: You acknowledge and agree that you will only use the Services when it is safe to do so.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to ask you for additional information verifying your identity prior processing your request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MileIQ
provenance_date: '2026-11-10'
provider_name: MileIQ
provider_slug: mileiq
slug: mileiq-eligibility
source_date: '2026-11-10'
source_filename: mileiq-eligibility.yml
source_heading: Eligibility
source_page: https://mileiq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MileIQ\naid: mileiq\nurl: https://mileiq.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Some services and features may not be available in all countries, in all languages, or in all operating\n    systems. You represent you are not located in a country subject to a U.S. Government embargo.\nentity_types:\n- type: business\n  text: If you are entering into an agreement with us on behalf of an entity or company, you will need to enter\n    into the Enterprise Customer Terms of Use found below.\nrestricted_uses:\n- summary: Use only when safe to do so\n\
  \  text: You acknowledge and agree that you will only use the Services when it is safe to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to ask you for additional information verifying your identity prior processing your\n    request.\nminimum_age:\n  value: '18'\n  text: The Services are intended solely for users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/mileiq/eligibility/mileiq-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from MileIQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Mileage Tracking
- Expense Management
- Transportation
- Tax
- Accounting
- Location
- Fleet Management
---
