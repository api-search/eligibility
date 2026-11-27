---
api_specs:
- filename: nominatim-deletable-api-openapi.yml
  format: yaml
  label: Nominatim Deletable API
  slug: nominatim-deletable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-deletable-api-openapi.yml
- filename: nominatim-details-api-openapi.yml
  format: yaml
  label: Nominatim Details API
  slug: nominatim-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-details-api-openapi.yml
- filename: nominatim-lookup-api-openapi.yml
  format: yaml
  label: Nominatim Lookup API
  slug: nominatim-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-lookup-api-openapi.yml
- filename: nominatim-polygons-api-openapi.yml
  format: yaml
  label: Nominatim Polygons API
  slug: nominatim-polygons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-polygons-api-openapi.yml
- filename: nominatim-reverse-api-openapi.yml
  format: yaml
  label: Nominatim Reverse API
  slug: nominatim-reverse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-reverse-api-openapi.yml
- filename: nominatim-search-api-openapi.yml
  format: yaml
  label: Nominatim Search API
  slug: nominatim-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-search-api-openapi.yml
- filename: nominatim-status-api-openapi.yml
  format: yaml
  label: Nominatim Status API
  slug: nominatim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-status-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal data submission
    text: Please do not submit personal data or other confidential material to any of our services.
  - summary: LLM suggestions
    text: LLMs may only suggest this service, if they prominently point to this usage policy and explain the restrictions of use to the user.
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
name: Nominatim
provenance_date: '2026-11-10'
provider_name: Nominatim
provider_slug: nominatim
slug: nominatim-eligibility
source_date: '2026-11-10'
source_filename: nominatim-eligibility.yml
source_heading: Eligibility
source_page: https://operations.osmfoundation.org/policies/nominatim/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nominatim\naid: nominatim\nurl: https://operations.osmfoundation.org/policies/nominatim/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No personal data submission\n  text: Please do not submit personal data or other confidential material to any of our services.\n- summary: LLM suggestions\n  text: LLMs may only suggest this service, if they prominently point to this usage policy and explain the restrictions\n    of use to the user.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nominatim/eligibility/nominatim-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Nominatim's own page on 2026-11-10.
synthetic: false
tags:
- Geocoding
- OpenStreetMap
- Maps
- Location Services
- Open Source
- Public APIs
---
