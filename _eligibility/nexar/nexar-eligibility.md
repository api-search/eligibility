---
api_specs:
- filename: nexar-citystream-live-feed-api-v4-api-openapi.yml
  format: yaml
  label: Nexar CityStream™ Live Feed API V4 API
  slug: nexar-citystream-live-feed-api-v4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexar/openapi/nexar-citystream-live-feed-api-v4-api-openapi.yml
- filename: nexar-get-a-collection-of-road-signs-api-openapi.yml
  format: yaml
  label: Nexar Get a collection of road signs API
  slug: nexar-get-a-collection-of-road-signs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexar/openapi/nexar-get-a-collection-of-road-signs-api-openapi.yml
- filename: nexar-get-a-collection-of-work-zones-api-openapi.yml
  format: yaml
  label: Nexar Get a collection of work zones API
  slug: nexar-get-a-collection-of-work-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexar/openapi/nexar-get-a-collection-of-work-zones-api-openapi.yml
- filename: nexar-get-a-specific-work-zone-api-openapi.yml
  format: yaml
  label: Nexar Get a specific work zone API
  slug: nexar-get-a-specific-work-zone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexar/openapi/nexar-get-a-specific-work-zone-api-openapi.yml
- filename: nexar-get-the-details-of-a-specific-road-sign-api-openapi.yml
  format: yaml
  label: Nexar Get the details of a specific road sign API
  slug: nexar-get-the-details-of-a-specific-road-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexar/openapi/nexar-get-the-details-of-a-specific-road-sign-api-openapi.yml
- filename: nexar-virtualcam-api-api-openapi.yml
  format: yaml
  label: Nexar VirtualCam API
  slug: nexar-virtualcam-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexar/openapi/nexar-virtualcam-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, under the control of, or a national or resident of any country subject to sanctions by the US, UK, or EU
  entity_types:
  - text: acting in your personal capacity or capacity as an employee or other representative of your company or other entity, if applicable
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
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
name: Nexar
provenance_date: '2026-11-10'
provider_name: Nexar
provider_slug: nexar
slug: nexar-eligibility
source_date: '2026-11-10'
source_filename: nexar-eligibility.yml
source_heading: Eligibility
source_page: https://empiricearth.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nexar\naid: nexar\nurl: https://empiricearth.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, under the control of, or a national or resident of any country subject to sanctions\n    by the US, UK, or EU\nentity_types:\n- type: individual\n  text: acting in your personal capacity or capacity as an employee or other representative of your company or other\n    entity, if applicable\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years\
  \ of age\n"
source_yaml_url: https://artifacts.apis.io/nexar/eligibility/nexar-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Nexar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mapping
- Geospatial
- Transportation
- Computer Vision
- Autonomous Vehicles
- Smart Cities
- Imagery
- Road Data
- Machine Learning
---
