---
api_specs:
- filename: geocode-farm-openapi-generated.yml
  format: yaml
  label: Geocode.Farm API
  slug: geocode-farm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocode-farm/openapi/_ae-authored/geocode-farm-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  - text: The terms “you” and “your” refer to the individual user or entity accessing or using our Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No resale of data
    text: You may NOT, without the express written permission of Geocode.Farm, resell the information or data provided.
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
name: Geocode.Farm
provenance_date: '2026-11-09'
provider_name: Geocode.Farm
provider_slug: geocode-farm
slug: geocode-farm-eligibility
source_date: '2026-11-09'
source_filename: geocode-farm-eligibility.yml
source_heading: Eligibility
source_page: https://geocodefarm.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Geocode.Farm\naid: geocode-farm\nurl: https://geocodefarm.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms\n- type: individual\n  text: The terms “you” and “your” refer to the individual user or entity accessing or using our Services.\nrestricted_uses:\n- summary: No resale of data\n  text: You may NOT, without the express written permission of Geocode.Farm,\
  \ resell the information or data provided.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/geocode-farm/eligibility/geocode-farm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Geocode.Farm's own page on 2026-11-09.
synthetic: false
tags:
- Geocoding
- Location
- Data
- Services
---
