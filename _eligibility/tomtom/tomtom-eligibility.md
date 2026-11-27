---
api_specs:
- filename: tomtom-additional-data-api-openapi.yml
  format: yaml
  label: TomTom Additional Data API
  slug: tomtom-additional-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-additional-data-api-openapi.yml
- filename: tomtom-batch-routing-api-openapi.yml
  format: yaml
  label: TomTom Batch Routing API
  slug: tomtom-batch-routing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-batch-routing-api-openapi.yml
- filename: tomtom-copyrights-api-openapi.yml
  format: yaml
  label: TomTom Copyrights API
  slug: tomtom-copyrights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-copyrights-api-openapi.yml
- filename: tomtom-filters-api-openapi.yml
  format: yaml
  label: TomTom Filters API
  slug: tomtom-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-filters-api-openapi.yml
- filename: tomtom-geocoding-api-openapi.yml
  format: yaml
  label: TomTom Geocoding API
  slug: tomtom-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-geocoding-api-openapi.yml
- filename: tomtom-raster-api-openapi.yml
  format: yaml
  label: TomTom Raster API
  slug: tomtom-raster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-raster-api-openapi.yml
- filename: tomtom-reachable-range-api-openapi.yml
  format: yaml
  label: TomTom Reachable Range API
  slug: tomtom-reachable-range-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-reachable-range-api-openapi.yml
- filename: tomtom-reverse-geocoding-api-openapi.yml
  format: yaml
  label: TomTom Reverse Geocoding API
  slug: tomtom-reverse-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-reverse-geocoding-api-openapi.yml
- filename: tomtom-routing-api-openapi.yml
  format: yaml
  label: TomTom Routing API
  slug: tomtom-routing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-routing-api-openapi.yml
- filename: tomtom-search-api-openapi.yml
  format: yaml
  label: TomTom Search API
  slug: tomtom-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-search-api-openapi.yml
- filename: tomtom-traffic-flow-api-openapi.yml
  format: yaml
  label: TomTom Traffic Flow API
  slug: tomtom-traffic-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-traffic-flow-api-openapi.yml
- filename: tomtom-traffic-incidents-api-openapi.yml
  format: yaml
  label: TomTom Traffic Incidents API
  slug: tomtom-traffic-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-traffic-incidents-api-openapi.yml
- filename: tomtom-traffic-tiles-api-openapi.yml
  format: yaml
  label: TomTom Traffic Tiles API
  slug: tomtom-traffic-tiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-traffic-tiles-api-openapi.yml
- filename: tomtom-vector-api-openapi.yml
  format: yaml
  label: TomTom Vector API
  slug: tomtom-vector-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-vector-api-openapi.yml
- filename: tomtom-wms-wmts-api-openapi.yml
  format: yaml
  label: TomTom WMS / WMTS API
  slug: tomtom-wms-wmts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-wms-wmts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Licensed Products and may not accept the Agreement, if you are barred from receiving the Licensed Products under the laws of the United States or other countries, including the country in which you are resident or from which you use the Licensed Products.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Traffic-law enforcement
    text: use the Licensed Product or any derivatives thereof for the purpose of enforcement of traffic laws
  - summary: In-flight, drone or high-risk systems
    text: the Licensed Products or any derivatives thereof for or in connection with in-flight or drone navigation or in any high-risk systems, devices, products or services
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: TomTom may reject any Online Registration Form at its sole and absolute discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TomTom
provenance_date: '2026-11-10'
provider_name: TomTom
provider_slug: tomtom
slug: tomtom-eligibility
source_date: '2026-11-10'
source_filename: tomtom-eligibility.yml
source_heading: Eligibility
source_page: https://docs.tomtom.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TomTom\naid: tomtom\nurl: https://docs.tomtom.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Licensed Products and may not accept the Agreement, if you are barred from receiving\n    the Licensed Products under the laws of the United States or other countries, including the country in which\n    you are resident or from which you use the Licensed Products.\nentity_types: []\nrestricted_uses:\n- summary: Traffic-law enforcement\n  text: use the Licensed Product or any derivatives thereof for the purpose of enforcement of traffic\
  \ laws\n- summary: In-flight, drone or high-risk systems\n  text: the Licensed Products or any derivatives thereof for or in connection with in-flight or drone navigation\n    or in any high-risk systems, devices, products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: TomTom may reject any Online Registration Form at its sole and absolute discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tomtom/eligibility/tomtom-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from TomTom's own page on 2026-11-10.
synthetic: false
tags:
- Maps
- Traffic
- Transportation
- Navigation
- Location
- Geospatial
- Routing
- Geocoding
- Mobility
---
