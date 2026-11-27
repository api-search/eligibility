---
api_specs:
- filename: mapbox-activity-api-openapi.yml
  format: yaml
  label: Mapbox Activity API
  slug: mapbox-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-activity-api-openapi.yml
- filename: mapbox-mapbox-tiling-service-api-api-openapi.yml
  format: yaml
  label: Mapbox Tiling Service API
  slug: mapbox-mapbox-tiling-service-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-mapbox-tiling-service-api-api-openapi.yml
- filename: mapbox-tilesets-api-openapi.yml
  format: yaml
  label: Mapbox Tilesets API
  slug: mapbox-tilesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-tilesets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of your company or another legal entity, you represent that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be 18 years or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Vehicle usage requires separate licenses
    text: If your Licensed Application is related to vehicle usage, you must purchase a separate development license for non-production use and a separate commercial license for production use under an active order
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
name: Mapbox
provenance_date: '2026-11-10'
provider_name: Mapbox
provider_slug: mapbox
slug: mapbox-eligibility
source_date: '2026-11-10'
source_filename: mapbox-eligibility.yml
source_heading: Eligibility
source_page: https://www.mapbox.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mapbox\naid: mapbox\nurl: https://www.mapbox.com/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of your company or another legal entity, you represent\n    that you have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Vehicle usage requires separate licenses\n  text: If your Licensed Application is related to vehicle usage, you must purchase a separate development license\n    for non-production use and a separate commercial license for production\
  \ use under an active order\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/mapbox/eligibility/mapbox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Mapbox's own page on 2026-11-10.
synthetic: false
tags:
- Mapping
- Maps
- Geospatial
- Location
- Geocoding
- Routing
---
