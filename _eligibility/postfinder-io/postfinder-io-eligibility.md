---
api_specs:
- filename: postfinder-io-nearby-api-openapi.yml
  format: yaml
  label: Postfinder Nearby API
  slug: postfinder-io-nearby-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-nearby-api-openapi.yml
- filename: postfinder-io-places-api-openapi.yml
  format: yaml
  label: Postfinder Places API
  slug: postfinder-io-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-places-api-openapi.yml
- filename: postfinder-io-postcodes-api-openapi.yml
  format: yaml
  label: Postfinder Postcodes API
  slug: postfinder-io-postcodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-postcodes-api-openapi.yml
- filename: postfinder-io-reference-api-openapi.yml
  format: yaml
  label: Postfinder Reference API
  slug: postfinder-io-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-reference-api-openapi.yml
- filename: postfinder-io-search-api-openapi.yml
  format: yaml
  label: Postfinder Search API
  slug: postfinder-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-search-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A person checks everything before it appears, and we may decline or remove anything at any time without giving a reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Postfinder
provenance_date: '2026-11-10'
provider_name: Postfinder
provider_slug: postfinder-io
slug: postfinder-io-eligibility
source_date: '2026-11-10'
source_filename: postfinder-io-eligibility.yml
source_heading: Eligibility
source_page: https://postfinder.io/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Postfinder\naid: postfinder-io\nurl: https://postfinder.io/en/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A person checks everything before it appears, and we may decline or remove anything at any time without\n    giving a reason.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/postfinder-io/eligibility/postfinder-io-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Postfinder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Address
- Autocomplete
- Logistics
- Australia
---
