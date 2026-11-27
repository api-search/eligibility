---
api_specs:
- filename: blazepizza-blazepizza-api-api-openapi.yml
  format: yaml
  label: Blazepizza Blazepizza API
  slug: blazepizza-blazepizza-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blazepizza/openapi/blazepizza-blazepizza-api-api-openapi.yml
- filename: blazepizza-cat-pic-api-openapi.yml
  format: yaml
  label: Blazepizza Cat Pic API
  slug: blazepizza-cat-pic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blazepizza/openapi/blazepizza-cat-pic-api-openapi.yml
- filename: blazepizza-foo-api-openapi.yml
  format: yaml
  label: Blazepizza Foo API
  slug: blazepizza-foo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blazepizza/openapi/blazepizza-foo-api-openapi.yml
- filename: blazepizza-http-api-openapi.yml
  format: yaml
  label: Blazepizza HTTP API
  slug: blazepizza-http-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blazepizza/openapi/blazepizza-http-api-openapi.yml
- filename: blazepizza-image-api-openapi.yml
  format: yaml
  label: Blazepizza Image API
  slug: blazepizza-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blazepizza/openapi/blazepizza-image-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Price and participation vary at U.S. and Canada Blaze Pizza locations.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Offer restrictions
    text: Cannot be combined with other offers or discounts.
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
name: Blazepizza
provenance_date: '2026-11-09'
provider_name: Blazepizza
provider_slug: blazepizza
slug: blazepizza-eligibility
source_date: '2026-11-09'
source_filename: blazepizza-eligibility.yml
source_heading: Eligibility
source_page: https://www.blazepizza.com/marketing-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blazepizza\naid: blazepizza\nurl: https://www.blazepizza.com/marketing-terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Price and participation vary at U.S. and Canada Blaze Pizza locations.\nentity_types: []\nrestricted_uses:\n- summary: Offer restrictions\n  text: Cannot be combined with other offers or discounts.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blazepizza/eligibility/blazepizza-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Blazepizza's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fast Casual
- Pizza
- Restaurant
- Franchise
---
