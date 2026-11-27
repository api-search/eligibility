---
api_specs:
- filename: qloo-com-analysis-api-openapi.yml
  format: yaml
  label: Qloo Analysis API
  slug: qloo-com-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-analysis-api-openapi.yml
- filename: qloo-com-audiences-api-openapi.yml
  format: yaml
  label: Qloo Audiences API
  slug: qloo-com-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-audiences-api-openapi.yml
- filename: qloo-com-entities-api-openapi.yml
  format: yaml
  label: Qloo Entities API
  slug: qloo-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-entities-api-openapi.yml
- filename: qloo-com-info-api-openapi.yml
  format: yaml
  label: Qloo Info API
  slug: qloo-com-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-info-api-openapi.yml
- filename: qloo-com-insights-api-openapi.yml
  format: yaml
  label: Qloo Insights API
  slug: qloo-com-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-insights-api-openapi.yml
- filename: qloo-com-search-api-openapi.yml
  format: yaml
  label: Qloo Search API
  slug: qloo-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-search-api-openapi.yml
- filename: qloo-com-tags-api-openapi.yml
  format: yaml
  label: Qloo Tags API
  slug: qloo-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-tags-api-openapi.yml
- filename: qloo-com-trends-api-openapi.yml
  format: yaml
  label: Qloo Trends API
  slug: qloo-com-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-trends-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: each individual granted a licensed seat is an “Authorized User” and is required to have a unique account and password
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you may not use the Services.
    value: '18'
  restricted_uses:
  - summary: Illegal use
    text: Using the Services for any illegal purpose.
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
name: Qloo
provenance_date: '2026-11-10'
provider_name: Qloo
provider_slug: qloo-com
slug: qloo-com-eligibility
source_date: '2026-11-10'
source_filename: qloo-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.qloo.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qloo\naid: qloo-com\nurl: https://www.qloo.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: each individual granted a licensed seat is an “Authorized User” and is required to have a unique account\n    and password\nrestricted_uses:\n- summary: Illegal use\n  text: Using the Services for any illegal purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you may not use the Services.\n"
source_yaml_url: https://artifacts.apis.io/qloo-com/eligibility/qloo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Qloo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cultural-Intelligence
- Data Analytics
- Personalization
---
