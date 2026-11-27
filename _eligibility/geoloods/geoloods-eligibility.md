---
api_specs:
- filename: geoloods-agent-api-openapi.yml
  format: yaml
  label: Geoloods Agent API
  slug: geoloods-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-agent-api-openapi.yml
- filename: geoloods-bbox-api-openapi.yml
  format: yaml
  label: Geoloods Bbox API
  slug: geoloods-bbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-bbox-api-openapi.yml
- filename: geoloods-countries-api-openapi.yml
  format: yaml
  label: Geoloods Countries API
  slug: geoloods-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-countries-api-openapi.yml
- filename: geoloods-geocode-api-openapi.yml
  format: yaml
  label: Geoloods Geocode API
  slug: geoloods-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-geocode-api-openapi.yml
- filename: geoloods-nearby-api-openapi.yml
  format: yaml
  label: Geoloods Nearby API
  slug: geoloods-nearby-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-nearby-api-openapi.yml
- filename: geoloods-search-api-openapi.yml
  format: yaml
  label: Geoloods Search API
  slug: geoloods-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be at least 16 years of age
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Use the Service for any illegal or unauthorized purpose
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
name: Geoloods
provenance_date: '2026-11-09'
provider_name: Geoloods
provider_slug: geoloods
slug: geoloods-eligibility
source_date: '2026-11-09'
source_filename: geoloods-eligibility.yml
source_heading: Eligibility
source_page: https://geoloods.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Geoloods\naid: geoloods\nurl: https://geoloods.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Use the Service for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Be at least 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/geoloods/eligibility/geoloods-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Geoloods's own page on 2026-11-09.
synthetic: false
tags:
- Geocoding
- Place Search
- Location
- Coordinates
- Mapping
- Geospatial
- Agents
- OpenAPI
- Llms.txt
---
