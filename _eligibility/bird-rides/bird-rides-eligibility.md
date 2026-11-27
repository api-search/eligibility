---
api_specs:
- filename: bird-rides-discovery-api-openapi.yml
  format: yaml
  label: Bird Discovery API
  slug: bird-rides-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bird-rides/openapi/bird-rides-discovery-api-openapi.yml
- filename: bird-rides-geofencing-api-openapi.yml
  format: yaml
  label: Bird Geofencing API
  slug: bird-rides-geofencing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bird-rides/openapi/bird-rides-geofencing-api-openapi.yml
- filename: bird-rides-pricing-api-openapi.yml
  format: yaml
  label: Bird Pricing API
  slug: bird-rides-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bird-rides/openapi/bird-rides-pricing-api-openapi.yml
- filename: bird-rides-realtime-api-openapi.yml
  format: yaml
  label: Bird Realtime API
  slug: bird-rides-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bird-rides/openapi/bird-rides-realtime-api-openapi.yml
- filename: bird-rides-stations-api-openapi.yml
  format: yaml
  label: Bird Stations API
  slug: bird-rides-stations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bird-rides/openapi/bird-rides-stations-api-openapi.yml
- filename: bird-rides-system-api-openapi.yml
  format: yaml
  label: Bird System API
  slug: bird-rides-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bird-rides/openapi/bird-rides-system-api-openapi.yml
- filename: bird-rides-vehicles-api-openapi.yml
  format: yaml
  label: Bird Vehicles API
  slug: bird-rides-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bird-rides/openapi/bird-rides-vehicles-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are over the age of 18, have the right and authority to enter into this Agreement
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18
    value: '18'
  restricted_uses:
  - summary: No unlawful or infringing posts
    text: You are prohibited from using the Services to post or send any unlawful, infringing, threatening, defamatory, libelous, obscene, pornographic or profane material
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You understand that you will need to create an account to have access to the Services, including Rental Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bird
provenance_date: '2026-11-09'
provider_name: Bird
provider_slug: bird-rides
slug: bird-rides-eligibility
source_date: '2026-11-09'
source_filename: bird-rides-eligibility.yml
source_heading: Eligibility
source_page: https://bird.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bird\naid: bird-rides\nurl: https://bird.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are over the age of 18, have the right and authority to enter into this Agreement\nrestricted_uses:\n- summary: No unlawful or infringing posts\n  text: You are prohibited from using the Services to post or send any unlawful, infringing, threatening, defamatory,\n    libelous, obscene, pornographic or profane material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You understand that\
  \ you will need to create an account to have access to the Services, including Rental\n    Services.\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/bird-rides/eligibility/bird-rides-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bird's own page on 2026-11-09.
synthetic: false
tags:
- Micromobility
- Shared Mobility
- Electric Scooters
- E-Scooter
- E-Bikes
- Bike Share
- Transportation
- Urban Mobility
- GBFS
- General Bikeshare Feed Specification
- Mobility Data Specification
- MDS
- Geofencing
- Cities
- Smart Cities
- Fleet Management
- Third Lane Mobility
- Mobility
---
