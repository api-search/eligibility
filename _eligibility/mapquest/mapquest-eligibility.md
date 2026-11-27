---
api_specs:
- filename: mapquest-directions-api-openapi.yml
  format: yaml
  label: MapQuest Directions API
  slug: mapquest-directions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapquest/openapi/mapquest-directions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: MapQuest makes no representation that the Materials are appropriate or available for use in locations outside the United States, and accessing it from territories where the Materials are illegal is prohibited.
  entity_types:
  - text: Any account you establish is for your personal use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Adult content, illegal activity, gambling, tobacco/alcohol sales to minors
    text: uses the Materials or MapQuest website in conjunction with adult content or promotes illegal activities, gambling, or the sale of tobacco or alcohol to persons under twenty-one (21) years of age.
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
name: MapQuest
provenance_date: '2026-11-10'
provider_name: MapQuest
provider_slug: mapquest
slug: mapquest-eligibility
source_date: '2026-11-10'
source_filename: mapquest-eligibility.yml
source_heading: Eligibility
source_page: https://hello.mapquest.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MapQuest\naid: mapquest\nurl: https://hello.mapquest.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: MapQuest makes no representation that the Materials are appropriate or available for use in locations outside\n    the United States, and accessing it from territories where the Materials are illegal is prohibited.\nentity_types:\n- type: individual\n  text: Any account you establish is for your personal use only.\nrestricted_uses:\n- summary: Adult content, illegal activity, gambling, tobacco/alcohol sales to minors\n  text: uses the Materials or MapQuest website\
  \ in conjunction with adult content or promotes illegal activities,\n    gambling, or the sale of tobacco or alcohol to persons under twenty-one (21) years of age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mapquest/eligibility/mapquest-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from MapQuest's own page on 2026-11-10.
synthetic: false
tags:
- Geocoding
- Mapping
- Maps
- Navigation
- Routing
- Traffic
---
