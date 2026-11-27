---
api_specs:
- filename: lightstream-backendauthenticationservice-api-openapi.yml
  format: yaml
  label: Lightstream BackendAuthenticationService API
  slug: lightstream-backendauthenticationservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-backendauthenticationservice-api-openapi.yml
- filename: lightstream-collectionservice-api-openapi.yml
  format: yaml
  label: Lightstream CollectionService API
  slug: lightstream-collectionservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-collectionservice-api-openapi.yml
- filename: lightstream-destinationservice-api-openapi.yml
  format: yaml
  label: Lightstream DestinationService API
  slug: lightstream-destinationservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-destinationservice-api-openapi.yml
- filename: lightstream-layerservice-api-openapi.yml
  format: yaml
  label: Lightstream LayerService API
  slug: lightstream-layerservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-layerservice-api-openapi.yml
- filename: lightstream-layoutservice-api-openapi.yml
  format: yaml
  label: Lightstream LayoutService API
  slug: lightstream-layoutservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-layoutservice-api-openapi.yml
- filename: lightstream-projectservice-api-openapi.yml
  format: yaml
  label: Lightstream ProjectService API
  slug: lightstream-projectservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-projectservice-api-openapi.yml
- filename: lightstream-publicauthenticationservice-api-openapi.yml
  format: yaml
  label: Lightstream PublicAuthenticationService API
  slug: lightstream-publicauthenticationservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-publicauthenticationservice-api-openapi.yml
- filename: lightstream-sourceservice-api-openapi.yml
  format: yaml
  label: Lightstream SourceService API
  slug: lightstream-sourceservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-sourceservice-api-openapi.yml
- filename: lightstream-authentication-service-api-openapi.yml
  format: yaml
  label: Lightstream Authentication Service API
  slug: lightstream-authentication-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-authentication-service-api-openapi.yml
- filename: lightstream-event-service-api-openapi.yml
  format: yaml
  label: Lightstream Event Service API
  slug: lightstream-event-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightstream/openapi/lightstream-event-service-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are using the Site from a country embargoed by the United States, or are on the United States Treasury Department's list of "Specially Designated Nationals," you agree that you will not engage in financial transactions, or conduct any commercial activities using or through the Site.
  entity_types:
  - text: Access to the Site is for your business use only and not for resale.
    type: business
  minimum_age:
    text: The Site is not available to persons under the age of 18
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: you will not use any products in violation of, or provide products to any person who is forbidden from receiving the product under, the Export Laws or any economic sanctions
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
name: Lightstream
provenance_date: '2026-11-09'
provider_name: Lightstream
provider_slug: lightstream
slug: lightstream-eligibility
source_date: '2026-11-09'
source_filename: lightstream-eligibility.yml
source_heading: Eligibility
source_page: https://api.stream/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lightstream\naid: lightstream\nurl: https://api.stream/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are using the Site from a country embargoed by the United States, or are on the United States Treasury\n    Department's list of \"Specially Designated Nationals,\" you agree that you will not engage in financial transactions,\n    or conduct any commercial activities using or through the Site.\nentity_types:\n- type: business\n  text: Access to the Site is for your business use only and not for resale.\nrestricted_uses:\n- summary: Export and sanctions\
  \ restrictions\n  text: you will not use any products in violation of, or provide products to any person who is forbidden from receiving\n    the product under, the Export Laws or any economic sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is not available to persons under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/lightstream/eligibility/lightstream-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lightstream's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Live Streaming
- Broadcasting
- WebRTC
- RTMP
- Media
- Compositing
- Real-Time
- Event
- gRPC
- Creator Tools
---
