---
api_specs:
- filename: car-api-account-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Account API
  slug: car-api-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-account-api-openapi.yml
- filename: car-api-auth-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Auth API
  slug: car-api-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-auth-api-openapi.yml
- filename: car-api-bodies-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Bodies API
  slug: car-api-bodies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-bodies-api-openapi.yml
- filename: car-api-colors-exterior-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Colors (Exterior) API
  slug: car-api-colors-exterior-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-colors-exterior-api-openapi.yml
- filename: car-api-colors-interior-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Colors (Interior) API
  slug: car-api-colors-interior-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-colors-interior-api-openapi.yml
- filename: car-api-data-feeds-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Data Feeds API
  slug: car-api-data-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-data-feeds-api-openapi.yml
- filename: car-api-engines-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Engines API
  slug: car-api-engines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-engines-api-openapi.yml
- filename: car-api-makes-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Makes API
  slug: car-api-makes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-makes-api-openapi.yml
- filename: car-api-mileages-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Mileages API
  slug: car-api-mileages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-mileages-api-openapi.yml
- filename: car-api-models-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Models API
  slug: car-api-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-models-api-openapi.yml
- filename: car-api-trims-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Trims API
  slug: car-api-trims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-trims-api-openapi.yml
- filename: car-api-vehicle-attributes-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Vehicle Attributes API
  slug: car-api-vehicle-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-vehicle-attributes-api-openapi.yml
- filename: car-api-vin-decoder-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Vin Decoder API
  slug: car-api-vin-decoder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-vin-decoder-api-openapi.yml
- filename: car-api-years-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Years API
  slug: car-api-years-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-years-api-openapi.yml
- filename: car-api-license-plate-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) License Plate API
  slug: car-api-license-plate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-license-plate-api-openapi.yml
- filename: car-api-obd-codes-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) OBD Codes API
  slug: car-api-obd-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-obd-codes-api-openapi.yml
- filename: car-api-sub-models-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Sub Models API
  slug: car-api-sub-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-sub-models-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are intended solely for users who are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Competing use of data
    text: You shall not use data obtained through the Services, including data obtained via the data feed, directly or indirectly, to create, populate, supplement, or otherwise materially contribute to any collection, compilation, database, or product that competes with or is substantially similar to the Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to certain features of the Services requires registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Car API (carapi.app)
provenance_date: '2026-11-09'
provider_name: Car API (carapi.app)
provider_slug: car-api
slug: car-api-eligibility
source_date: '2026-11-09'
source_filename: car-api-eligibility.yml
source_heading: Eligibility
source_page: https://carapi.app/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Car API (carapi.app)\naid: car-api\nurl: https://carapi.app/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competing use of data\n  text: You shall not use data obtained through the Services, including data obtained via the data feed, directly\n    or indirectly, to create, populate, supplement, or otherwise materially contribute to any collection, compilation,\n    database, or product that competes with or is substantially similar to the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: Access to certain features of the Services requires registration.\nminimum_age:\n  value: '18'\n  text: The Services are intended solely for users who are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/car-api/eligibility/car-api-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Car API (carapi.app)'s own page on 2026-11-09.
synthetic: false
tags:
- Automobiles
- Automotive Data
- Cars
- License Plate Decoder
- OBD-II
- Power-Sports
- Vehicle API
- Vehicle Specifications
- Vehicles
- VIN Decoding
---
