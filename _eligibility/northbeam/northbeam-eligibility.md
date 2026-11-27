---
api_specs:
- filename: northbeam-attribution-models-api-openapi.yml
  format: yaml
  label: Northbeam Attribution Models API
  slug: northbeam-attribution-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northbeam/openapi/northbeam-attribution-models-api-openapi.yml
- filename: northbeam-breakdowns-api-openapi.yml
  format: yaml
  label: Northbeam Breakdowns API
  slug: northbeam-breakdowns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northbeam/openapi/northbeam-breakdowns-api-openapi.yml
- filename: northbeam-data-export-api-openapi.yml
  format: yaml
  label: Northbeam Data Export API
  slug: northbeam-data-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northbeam/openapi/northbeam-data-export-api-openapi.yml
- filename: northbeam-metrics-api-openapi.yml
  format: yaml
  label: Northbeam Metrics API
  slug: northbeam-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northbeam/openapi/northbeam-metrics-api-openapi.yml
- filename: northbeam-orders-api-openapi.yml
  format: yaml
  label: Northbeam Orders API
  slug: northbeam-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northbeam/openapi/northbeam-orders-api-openapi.yml
- filename: northbeam-spend-api-openapi.yml
  format: yaml
  label: Northbeam Spend API
  slug: northbeam-spend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northbeam/openapi/northbeam-spend-api-openapi.yml
- filename: northbeam-spend-hourly-api-openapi.yml
  format: yaml
  label: Northbeam Spend Hourly API
  slug: northbeam-spend-hourly-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northbeam/openapi/northbeam-spend-hourly-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive personal information
    text: Customer shall not store, or process Sensitive Personal Information in the Company Solution, including but not limited to Personal Health Information
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
name: Northbeam
provenance_date: '2026-11-10'
provider_name: Northbeam
provider_slug: northbeam
slug: northbeam-eligibility
source_date: '2026-11-10'
source_filename: northbeam-eligibility.yml
source_heading: Eligibility
source_page: https://www.northbeam.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Northbeam\naid: northbeam\nurl: https://www.northbeam.io/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sensitive personal information\n  text: Customer shall not store, or process Sensitive Personal Information in the Company Solution, including but\n    not limited to Personal Health Information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/northbeam/eligibility/northbeam-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Northbeam's own page on 2026-11-10.
synthetic: false
tags:
- Marketing Attribution
- Multi-Touch Attribution
- E-Commerce
- ROAS
- Media Mix Modeling
- Creative Analytics
- Performance Marketing
- Advertising
- Marketing Analytics
- Agents
- Attribution
---
