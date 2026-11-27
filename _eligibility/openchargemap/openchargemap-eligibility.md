---
api_specs:
- filename: openchargemap-comment-api-openapi.yml
  format: yaml
  label: Open Charge Map Comment API
  slug: openchargemap-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openchargemap/openapi/openchargemap-comment-api-openapi.yml
- filename: openchargemap-mediaitem-api-openapi.yml
  format: yaml
  label: Open Charge Map Mediaitem API
  slug: openchargemap-mediaitem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openchargemap/openapi/openchargemap-mediaitem-api-openapi.yml
- filename: openchargemap-poi-api-openapi.yml
  format: yaml
  label: Open Charge Map Poi API
  slug: openchargemap-poi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openchargemap/openapi/openchargemap-poi-api-openapi.yml
- filename: openchargemap-profile-api-openapi.yml
  format: yaml
  label: Open Charge Map Profile API
  slug: openchargemap-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openchargemap/openapi/openchargemap-profile-api-openapi.yml
- filename: openchargemap-open-api-api-openapi.yml
  format: yaml
  label: Open Charge Map Open API
  slug: openchargemap-open-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openchargemap/openapi/openchargemap-open-api-api-openapi.yml
- filename: openchargemap-reference-data-api-openapi.yml
  format: yaml
  label: Open Charge Map Reference Data API
  slug: openchargemap-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openchargemap/openapi/openchargemap-reference-data-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If your organisation has electric vehicle charging equipment location information then we would like you to share that information with Open Charge Map.
    type: other
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
name: Open Charge Map
provenance_date: '2026-11-10'
provider_name: Open Charge Map
provider_slug: openchargemap
slug: openchargemap-eligibility
source_date: '2026-11-10'
source_filename: openchargemap-eligibility.yml
source_heading: Eligibility
source_page: https://openchargemap.org/about/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Open Charge Map\naid: openchargemap\nurl: https://openchargemap.org/about/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: If your organisation has electric vehicle charging equipment location information then we would like you\n    to share that information with Open Charge Map.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openchargemap/eligibility/openchargemap-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Open Charge Map's own page on 2026-11-10.
synthetic: false
tags:
- Electric Vehicles
- EV Charging
- Charging Stations
- Points of Interest
- Open Data
- Geospatial
- Transportation
- Clean Energy
- Crowdsourced
- Registry
---
