---
api_specs:
- filename: postalcodes-info-downloads-api-openapi.yml
  format: yaml
  label: PostalCodes.info Downloads API
  slug: postalcodes-info-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalcodes-info/openapi/postalcodes-info-downloads-api-openapi.yml
- filename: postalcodes-info-lookup-pages-api-openapi.yml
  format: yaml
  label: PostalCodes.info Lookup Pages API
  slug: postalcodes-info-lookup-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalcodes-info/openapi/postalcodes-info-lookup-pages-api-openapi.yml
- filename: postalcodes-info-search-api-openapi.yml
  format: yaml
  label: PostalCodes.info Search API
  slug: postalcodes-info-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalcodes-info/openapi/postalcodes-info-search-api-openapi.yml
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
  - summary: Misrepresenting centroids as official boundaries
    text: You may not claim our geocoding centroids as official government-certified property boundaries (they are statistical centroids).
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
name: PostalCodes.info
provenance_date: '2026-11-10'
provider_name: PostalCodes.info
provider_slug: postalcodes-info
slug: postalcodes-info-eligibility
source_date: '2026-11-10'
source_filename: postalcodes-info-eligibility.yml
source_heading: Eligibility
source_page: https://postalcodes.info/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PostalCodes.info\naid: postalcodes-info\nurl: https://postalcodes.info/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Misrepresenting centroids as official boundaries\n  text: You may not claim our geocoding centroids as official government-certified property boundaries (they are\n    statistical centroids).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/postalcodes-info/eligibility/postalcodes-info-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from PostalCodes.info's own page on 2026-11-10.
synthetic: false
tags:
- Postal Codes
- Geocoding
- Open Data
- Address Validation
- Logistics
---
