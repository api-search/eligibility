---
api_specs:
- filename: gribstream-com-account-api-openapi.yml
  format: yaml
  label: gribstream-com Account API
  slug: gribstream-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gribstream-com/openapi/gribstream-com-account-api-openapi.yml
- filename: gribstream-com-catalog-api-openapi.yml
  format: yaml
  label: gribstream-com Catalog API
  slug: gribstream-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gribstream-com/openapi/gribstream-com-catalog-api-openapi.yml
- filename: gribstream-com-grid-coordinates-api-openapi.yml
  format: yaml
  label: gribstream-com Grid coordinates API
  slug: gribstream-com-grid-coordinates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gribstream-com/openapi/gribstream-com-grid-coordinates-api-openapi.yml
- filename: gribstream-com-weather-data-api-openapi.yml
  format: yaml
  label: gribstream-com Weather data API
  slug: gribstream-com-weather-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gribstream-com/openapi/gribstream-com-weather-data-api-openapi.yml
claim_count: 2
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
  - summary: High-risk decisions
    text: You must not rely on the Service as the sole source for safety-of-life, emergency, aviation, medical, legal, financial, regulated, or similarly high-risk decisions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must create an account and authenticate using an accepted authentication provider, such as Google or GitHub.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: gribstream-com
provenance_date: '2026-11-09'
provider_name: gribstream-com
provider_slug: gribstream-com
slug: gribstream-com-eligibility
source_date: '2026-11-09'
source_filename: gribstream-com-eligibility.yml
source_heading: Eligibility
source_page: https://gribstream.com/tos.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: gribstream-com\naid: gribstream-com\nurl: https://gribstream.com/tos.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk decisions\n  text: You must not rely on the Service as the sole source for safety-of-life, emergency, aviation, medical, legal,\n    financial, regulated, or similarly high-risk decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must create an account and authenticate using an accepted authentication provider,\n    such as Google or GitHub.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gribstream-com/eligibility/gribstream-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from gribstream-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Weather
- Forecast
- Data
---
