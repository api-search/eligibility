---
api_specs:
- filename: life360-product-api-openapi.yml
  format: yaml
  label: Life360 Product API
  slug: life360-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/life360/openapi/life360-product-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all Service features may be available in your country.
  entity_types:
  - text: The Products and Services are intended for use by individuals and not by entities or businesses
    type: individual
  - text: The Products and Services are intended for use by individuals and not by entities or businesses (for example, church groups, schools, corporations or businesses).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial purposes prohibited
    text: using the Services for any commercial purposes
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
name: Life360
provenance_date: '2026-11-09'
provider_name: Life360
provider_slug: life360
slug: life360-eligibility
source_date: '2026-11-09'
source_filename: life360-eligibility.yml
source_heading: Eligibility
source_page: https://legal.corp.life360.com/hc/en-us/articles/16124856472471-Life360-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Life360\naid: life360\nurl: https://legal.corp.life360.com/hc/en-us/articles/16124856472471-Life360-Terms-of-Service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Not all Service features may be available in your country.\nentity_types:\n- type: individual\n  text: The Products and Services are intended for use by individuals and not by entities or businesses\n- type: business\n  text: The Products and Services are intended for use by individuals and not by entities or businesses (for example,\n    church groups, schools, corporations or businesses).\nrestricted_uses:\n\
  - summary: Commercial purposes prohibited\n  text: using the Services for any commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/life360/eligibility/life360-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Life360's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Family Safety
- Location
- GPS Tracking
- Bluetooth Trackers
- Mobile App
- Driving Safety
- Wearables
- Subscription
---
