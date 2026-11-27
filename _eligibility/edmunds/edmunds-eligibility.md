---
api_specs:
- filename: edmunds-vehicle-api-openapi.yml
  format: yaml
  label: Edmunds Vehicle API
  slug: edmunds-vehicle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edmunds/openapi/edmunds-vehicle-api-openapi.yml
- filename: edmunds-aiplugin-api-openapi.yml
  format: yaml
  label: Edmunds Aiplugin API
  slug: edmunds-aiplugin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edmunds/openapi/edmunds-aiplugin-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Developer” “you” and “your” mean the entity that owns or controls any Developer Application.
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited product categories
    text: 'You will not use the Edmunds APIs in connection with or to promote any products, services, or materials that constitute, promote or are used primarily for the purpose of dealing in: spyware, adware, or other malicious programs or code,'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: conditioned on Edmunds’ issuing you an API Key
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Edmunds
provenance_date: '2026-11-09'
provider_name: Edmunds
provider_slug: edmunds
slug: edmunds-eligibility
source_date: '2026-11-09'
source_filename: edmunds-eligibility.yml
source_heading: Eligibility
source_page: https://developer.edmunds.com/terms_of_service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Edmunds\naid: edmunds\nurl: https://developer.edmunds.com/terms_of_service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: “Developer” “you” and “your” mean the entity that owns or controls any Developer Application.\nrestricted_uses:\n- summary: Prohibited product categories\n  text: 'You will not use the Edmunds APIs in connection with or to promote any products, services, or materials\n    that constitute, promote or are used primarily for the purpose of dealing in: spyware, adware, or other malicious\n    programs or code,'\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: conditioned on Edmunds’ issuing you an API Key\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/edmunds/eligibility/edmunds-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Edmunds's own page on 2026-11-09.
synthetic: false
tags:
- Automobiles
- Cars
- Vehicles
- Vehicle Data
- Dealership
- Reviews
- Pricing
- Automotive
---
