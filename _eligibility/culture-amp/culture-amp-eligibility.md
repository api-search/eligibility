---
api_specs:
- filename: culture-amp-employees-api-openapi.yml
  format: yaml
  label: Culture Amp Employees API
  slug: culture-amp-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culture-amp/openapi/culture-amp-employees-api-openapi.yml
- filename: culture-amp-performance-api-openapi.yml
  format: yaml
  label: Culture Amp Performance API
  slug: culture-amp-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culture-amp/openapi/culture-amp-performance-api-openapi.yml
- filename: culture-amp-surveys-api-openapi.yml
  format: yaml
  label: Culture Amp Surveys API
  slug: culture-amp-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culture-amp/openapi/culture-amp-surveys-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer means the entity identified in the Service Order.
    type: business
  minimum_age:
    text: Users meet any applicable minimum age or eligibility requirements.
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: The Customer must ensure that the Services are used only for lawful purposes and in accordance with this Agreement.
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
name: Culture Amp
provenance_date: '2026-11-09'
provider_name: Culture Amp
provider_slug: culture-amp
slug: culture-amp-eligibility
source_date: '2026-11-09'
source_filename: culture-amp-eligibility.yml
source_heading: Eligibility
source_page: https://www.cultureamp.com/company/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Culture Amp\naid: culture-amp\nurl: https://www.cultureamp.com/company/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer means the entity identified in the Service Order.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: The Customer must ensure that the Services are used only for lawful purposes and in accordance with this\n    Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Users meet any applicable minimum age or eligibility\
  \ requirements.\n"
source_yaml_url: https://artifacts.apis.io/culture-amp/eligibility/culture-amp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Culture Amp's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Employee Engagement
- Performance Management
- People Analytics
- Surveys
- Australia
---
