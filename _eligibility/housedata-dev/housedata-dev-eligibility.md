---
api_specs:
- filename: housedata-dev-openapi-generated.yml
  format: yaml
  label: housedata-dev API
  slug: housedata-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housedata-dev/openapi/_ae-authored/housedata-dev-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use HouseData on behalf of an organisation, you agree on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment, profiling or targeting individuals
    text: harass, profile or target individuals, or build datasets about identified people beyond what a lawful purpose requires
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
name: housedata-dev
provenance_date: '2026-11-09'
provider_name: housedata-dev
provider_slug: housedata-dev
slug: housedata-dev-eligibility
source_date: '2026-11-09'
source_filename: housedata-dev-eligibility.yml
source_heading: Eligibility
source_page: https://housedata.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: housedata-dev\naid: housedata-dev\nurl: https://housedata.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use HouseData on behalf of an organisation, you agree on its behalf.\nrestricted_uses:\n- summary: Harassment, profiling or targeting individuals\n  text: harass, profile or target individuals, or build datasets about identified people beyond what a lawful purpose\n    requires\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/housedata-dev/eligibility/housedata-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from housedata-dev's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Zillow
- Data API
- US
- Property
---
