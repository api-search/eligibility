---
api_specs:
- filename: iplocate-openapi.yml
  format: yaml
  label: IPLocate API
  slug: iplocate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iplocate/openapi/iplocate-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Locating individuals
    text: 'You must not: use our geolocation data to locate, or attempt to locate, any specific person or group of people'
  - summary: Overstated accuracy claims
    text: make any claims, or imply, or suggest, that the accuracy of geolocation data is greater than the accuracy we have described in these terms
  - summary: Unlawful decisions from geolocation
    text: make any claim or decision based on geolocation data that violates local law
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
name: IPLocate (formerly GeoIPs)
provenance_date: '2026-11-09'
provider_name: IPLocate (formerly GeoIPs)
provider_slug: iplocate
slug: iplocate-eligibility
source_date: '2026-11-09'
source_filename: iplocate-eligibility.yml
source_heading: Eligibility
source_page: https://www.iplocate.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IPLocate (formerly GeoIPs)\naid: iplocate\nurl: https://www.iplocate.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human.\nrestricted_uses:\n- summary: Locating individuals\n  text: 'You must not: use our geolocation data to locate, or attempt to locate, any specific person or group of\n    people'\n- summary: Overstated accuracy claims\n  text: make any claims, or imply, or suggest, that the accuracy of geolocation data is greater than the accuracy\n    we have described in these terms\n- summary: Unlawful\
  \ decisions from geolocation\n  text: make any claim or decision based on geolocation data that violates local law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/iplocate/eligibility/iplocate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from IPLocate (formerly GeoIPs)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- IP Geolocation
- Threat Detection
- Privacy
- Data
---
