---
api_specs:
- filename: pic2svg-com-trace-api-openapi.yml
  format: yaml
  label: pic2svg Trace API
  slug: pic2svg-com-trace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pic2svg-com/openapi/pic2svg-com-trace-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live, to create an account or subscribe.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live, to create an account or subscribe.
    value: '18'
  restricted_uses:
  - summary: Unpermitted image submissions
    text: do not submit anything you are not permitted to send to our servers.
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
name: pic2svg
provenance_date: '2026-11-10'
provider_name: pic2svg
provider_slug: pic2svg-com
slug: pic2svg-com-eligibility
source_date: '2026-11-10'
source_filename: pic2svg-com-eligibility.yml
source_heading: Eligibility
source_page: https://pic2svg.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pic2svg\naid: pic2svg-com\nurl: https://pic2svg.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live, to create an account or subscribe.\nrestricted_uses:\n- summary: Unpermitted image submissions\n  text: do not submit anything you are not permitted to send to our servers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where\
  \ you live, to create an account or subscribe.\n"
source_yaml_url: https://artifacts.apis.io/pic2svg-com/eligibility/pic2svg-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from pic2svg's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Image Conversion
- SVG
- Design Tools
---
