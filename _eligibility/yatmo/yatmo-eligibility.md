---
api_specs:
- filename: yatmo-bikepaths-api-openapi.yml
  format: yaml
  label: Yatmo Bike Paths API
  slug: yatmo-bikepaths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-bikepaths-api-openapi.yml
- filename: yatmo-categories-api-openapi.yml
  format: yaml
  label: Yatmo Categories API
  slug: yatmo-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-categories-api-openapi.yml
- filename: yatmo-enrichment-api-openapi.yml
  format: yaml
  label: Yatmo Enrichment API
  slug: yatmo-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-enrichment-api-openapi.yml
- filename: yatmo-frenchneighbourhoods-api-openapi.yml
  format: yaml
  label: Yatmo French Neighbourhoods API
  slug: yatmo-frenchneighbourhoods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-frenchneighbourhoods-api-openapi.yml
- filename: yatmo-geolocation-api-openapi.yml
  format: yaml
  label: Yatmo Geolocation API
  slug: yatmo-geolocation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-geolocation-api-openapi.yml
- filename: yatmo-geopositionencoder-api-openapi.yml
  format: yaml
  label: Yatmo Geo Position Encoder API
  slug: yatmo-geopositionencoder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-geopositionencoder-api-openapi.yml
- filename: yatmo-image-api-openapi.yml
  format: yaml
  label: Yatmo Image API
  slug: yatmo-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-image-api-openapi.yml
- filename: yatmo-immotopcategories-api-openapi.yml
  format: yaml
  label: Yatmo Immotop Categories API
  slug: yatmo-immotopcategories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-immotopcategories-api-openapi.yml
- filename: yatmo-isochrone-api-openapi.yml
  format: yaml
  label: Yatmo Isochrone API
  slug: yatmo-isochrone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-isochrone-api-openapi.yml
- filename: yatmo-nearcheck-api-openapi.yml
  format: yaml
  label: Yatmo Near Check API
  slug: yatmo-nearcheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-nearcheck-api-openapi.yml
- filename: yatmo-neighbourhood-api-openapi.yml
  format: yaml
  label: Yatmo Neighbourhood API
  slug: yatmo-neighbourhood-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-neighbourhood-api-openapi.yml
- filename: yatmo-points-api-openapi.yml
  format: yaml
  label: Yatmo Points API
  slug: yatmo-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-points-api-openapi.yml
- filename: yatmo-route-api-openapi.yml
  format: yaml
  label: Yatmo Route API
  slug: yatmo-route-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-route-api-openapi.yml
- filename: yatmo-scores-api-openapi.yml
  format: yaml
  label: Yatmo Scores API
  slug: yatmo-scores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-scores-api-openapi.yml
- filename: yatmo-shape-api-openapi.yml
  format: yaml
  label: Yatmo Shape API
  slug: yatmo-shape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-shape-api-openapi.yml
- filename: yatmo-simplifiedcategories-api-openapi.yml
  format: yaml
  label: Yatmo Simplified Categories API
  slug: yatmo-simplifiedcategories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-simplifiedcategories-api-openapi.yml
- filename: yatmo-summary-api-openapi.yml
  format: yaml
  label: Yatmo Summary API
  slug: yatmo-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yatmo/openapi/yatmo-summary-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: toute personne physique ou morale qui commande des services au prestataire
    type: individual
  - text: toute personne physique ou morale qui commande des services au prestataire
    type: business
  minimum_age:
    text: null
    value: null
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
name: Yatmo
provenance_date: '2026-11-10'
provider_name: Yatmo
provider_slug: yatmo
slug: yatmo-eligibility
source_date: '2026-11-10'
source_filename: yatmo-eligibility.yml
source_heading: Eligibility
source_page: https://yatmo.com/fr/legal/termsofsales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yatmo\naid: yatmo\nurl: https://yatmo.com/fr/legal/termsofsales\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: toute personne physique ou morale qui commande des services au prestataire\n- type: business\n  text: toute personne physique ou morale qui commande des services au prestataire\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yatmo/eligibility/yatmo-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Yatmo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Location Intelligence
- MappingAPI
- POI
---
