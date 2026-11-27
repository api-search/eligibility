---
api_specs:
- filename: google-maps-pollen-forecast-api-openapi.yml
  format: yaml
  label: Google Maps Platform Maps Pollen Forecast API
  slug: google-maps-pollen-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-pollen-forecast-api-openapi.yml
- filename: google-maps-address-validation-v1-api-openapi.yml
  format: yaml
  label: Google Maps Platform Address Validation V1 API
  slug: google-maps-address-validation-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-address-validation-v1-api-openapi.yml
- filename: google-maps-air-quality-currentconditions-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality CurrentConditions API
  slug: google-maps-air-quality-currentconditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-currentconditions-api-openapi.yml
- filename: google-maps-air-quality-forecast-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality Forecast API
  slug: google-maps-air-quality-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-forecast-api-openapi.yml
- filename: google-maps-air-quality-history-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality History API
  slug: google-maps-air-quality-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-history-api-openapi.yml
- filename: google-maps-air-quality-maptypes-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality MapTypes API
  slug: google-maps-air-quality-maptypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-maptypes-api-openapi.yml
- filename: google-maps-area-insights-v1-api-openapi.yml
  format: yaml
  label: Google Maps Platform Area Insights V1 API
  slug: google-maps-area-insights-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-area-insights-v1-api-openapi.yml
- filename: google-maps-pollen-maptypes-api-openapi.yml
  format: yaml
  label: Google Maps Platform Pollen MapTypes API
  slug: google-maps-pollen-maptypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-pollen-maptypes-api-openapi.yml
- filename: google-maps-solar-buildinginsights-api-openapi.yml
  format: yaml
  label: Google Maps Platform Solar BuildingInsights API
  slug: google-maps-solar-buildinginsights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-solar-buildinginsights-api-openapi.yml
- filename: google-maps-solar-datalayers-api-openapi.yml
  format: yaml
  label: Google Maps Platform Solar DataLayers API
  slug: google-maps-solar-datalayers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-solar-datalayers-api-openapi.yml
- filename: google-maps-solar-geotiff-api-openapi.yml
  format: yaml
  label: Google Maps Platform Solar GeoTiff API
  slug: google-maps-solar-geotiff-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-solar-geotiff-api-openapi.yml
- filename: google-maps-street-view-publish-photo-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish Photo API
  slug: google-maps-street-view-publish-photo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photo-api-openapi.yml
- filename: google-maps-street-view-publish-photos-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish Photos API
  slug: google-maps-street-view-publish-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photos-api-openapi.yml
- filename: google-maps-street-view-publish-photosequence-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish PhotoSequence API
  slug: google-maps-street-view-publish-photosequence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photosequence-api-openapi.yml
- filename: google-maps-street-view-publish-photosequences-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish PhotoSequences API
  slug: google-maps-street-view-publish-photosequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photosequences-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer is a U.S. federal government entity then the following applies
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: 'access or use the Services: (i) for High Risk Activities'
  - summary: Health information under HIPAA
    text: to transmit, store, or process health information subject to United States HIPAA regulations
  - summary: Children's services under COPPA
    text: in a Customer Application that would be deemed to be a "Website or online service directed to children" under the Children’s Online Privacy Protection Act (COPPA)
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
name: Google Maps Platform
provenance_date: '2026-11-09'
provider_name: Google Maps Platform
provider_slug: google-maps
slug: google-maps-eligibility
source_date: '2026-11-09'
source_filename: google-maps-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/maps-platform/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Maps Platform\naid: google-maps\nurl: https://cloud.google.com/maps-platform/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If Customer is a U.S. federal government entity then the following applies\nrestricted_uses:\n- summary: High Risk Activities\n  text: 'access or use the Services: (i) for High Risk Activities'\n- summary: Health information under HIPAA\n  text: to transmit, store, or process health information subject to United States HIPAA regulations\n- summary: Children's services under COPPA\n\
  \  text: in a Customer Application that would be deemed to be a \"Website or online service directed to children\"\n    under the Children’s Online Privacy Protection Act (COPPA)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-maps/eligibility/google-maps-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Google Maps Platform's own page on 2026-11-09.
synthetic: false
tags:
- Environment
- Geocoding
- Geolocation
- Maps
- Navigation
- Places
- Routing
- Solar
- Geospatial
---
