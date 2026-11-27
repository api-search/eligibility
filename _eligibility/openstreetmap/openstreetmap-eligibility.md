---
api_specs:
- filename: openstreetmap-capabilities-api-openapi.yml
  format: yaml
  label: OpenStreetMap Capabilities API
  slug: openstreetmap-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-capabilities-api-openapi.yml
- filename: openstreetmap-changesets-api-openapi.yml
  format: yaml
  label: OpenStreetMap Changesets API
  slug: openstreetmap-changesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-changesets-api-openapi.yml
- filename: openstreetmap-map-data-api-openapi.yml
  format: yaml
  label: OpenStreetMap Map Data API
  slug: openstreetmap-map-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-map-data-api-openapi.yml
- filename: openstreetmap-nodes-api-openapi.yml
  format: yaml
  label: OpenStreetMap Nodes API
  slug: openstreetmap-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-nodes-api-openapi.yml
- filename: openstreetmap-notes-api-openapi.yml
  format: yaml
  label: OpenStreetMap Notes API
  slug: openstreetmap-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-notes-api-openapi.yml
- filename: openstreetmap-relations-api-openapi.yml
  format: yaml
  label: OpenStreetMap Relations API
  slug: openstreetmap-relations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-relations-api-openapi.yml
- filename: openstreetmap-users-api-openapi.yml
  format: yaml
  label: OpenStreetMap Users API
  slug: openstreetmap-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-users-api-openapi.yml
- filename: openstreetmap-ways-api-openapi.yml
  format: yaml
  label: OpenStreetMap Ways API
  slug: openstreetmap-ways-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-ways-api-openapi.yml
- filename: openstreetmap-geocoding-api-openapi.yml
  format: yaml
  label: OpenStreetMap Geocoding API
  slug: openstreetmap-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-geocoding-api-openapi.yml
- filename: openstreetmap-status-api-openapi.yml
  format: yaml
  label: OpenStreetMap Status API
  slug: openstreetmap-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-status-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent you are not, and are not controlled by, an individual, organization or entity organized or located in a country or territory that is the target of sanctions imposed
  entity_types:
  - text: You must be 13 years or older to use the Services.
    type: individual
  - text: If you are entering into this agreement on behalf of your company or another legal entity, you represent that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be 13 years or older to use the Services.
    value: '13'
  restricted_uses:
  - summary: Dangerous businesses
    text: Operate dangerous businesses such as emergency services or air traffic control, where the use or failure of the Services could lead to death, personal injury or significant property damage;
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
name: OpenStreetMap
provenance_date: '2026-11-10'
provider_name: OpenStreetMap
provider_slug: openstreetmap
slug: openstreetmap-eligibility
source_date: '2026-11-10'
source_filename: openstreetmap-eligibility.yml
source_heading: Eligibility
source_page: https://osmfoundation.org/wiki/Terms_of_Use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenStreetMap\naid: openstreetmap\nurl: https://osmfoundation.org/wiki/Terms_of_Use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent you are not, and are not controlled by, an individual, organization or entity organized or\n    located in a country or territory that is the target of sanctions imposed\nentity_types:\n- type: individual\n  text: You must be 13 years or older to use the Services.\n- type: business\n  text: If you are entering into this agreement on behalf of your company or another legal entity, you represent\n    that you have the authority to bind that\
  \ entity to these Terms\nrestricted_uses:\n- summary: Dangerous businesses\n  text: Operate dangerous businesses such as emergency services or air traffic control, where the use or failure\n    of the Services could lead to death, personal injury or significant property damage;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/openstreetmap/eligibility/openstreetmap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from OpenStreetMap's own page on 2026-11-10.
synthetic: false
tags:
- Geospatial
- Mapping
- Open Data
- Geocoding
- Editing
- OpenStreetMap
---
