---
api_specs:
- filename: toolaby-app-analytics-api-openapi.yml
  format: yaml
  label: toolaby-app Analytics API
  slug: toolaby-app-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-analytics-api-openapi.yml
- filename: toolaby-app-customers-api-openapi.yml
  format: yaml
  label: toolaby-app Customers API
  slug: toolaby-app-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-customers-api-openapi.yml
- filename: toolaby-app-grants-api-openapi.yml
  format: yaml
  label: toolaby-app Grants API
  slug: toolaby-app-grants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-grants-api-openapi.yml
- filename: toolaby-app-uses-api-openapi.yml
  format: yaml
  label: toolaby-app Uses API
  slug: toolaby-app-uses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-uses-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A workspace is yours, or your company's.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful extensions
    text: Sell or ship anything unlawful, deceptive, or that harms the people who install it
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
name: toolaby-app
provenance_date: '2026-11-10'
provider_name: toolaby-app
provider_slug: toolaby-app
slug: toolaby-app-eligibility
source_date: '2026-11-10'
source_filename: toolaby-app-eligibility.yml
source_heading: Eligibility
source_page: https://toolaby.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: toolaby-app\naid: toolaby-app\nurl: https://toolaby.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A workspace is yours, or your company's.\nrestricted_uses:\n- summary: Unlawful or harmful extensions\n  text: Sell or ship anything unlawful, deceptive, or that harms the people who install it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/toolaby-app/eligibility/toolaby-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from toolaby-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Chrome Extension
- Stripe
- Licensing
---
