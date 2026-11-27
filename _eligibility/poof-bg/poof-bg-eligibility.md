---
api_specs:
- filename: poof-bg-account-api-openapi.yml
  format: yaml
  label: poof-bg Account API
  slug: poof-bg-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/poof-bg/openapi/poof-bg-account-api-openapi.yml
- filename: poof-bg-background-removal-api-openapi.yml
  format: yaml
  label: poof-bg Background Removal API
  slug: poof-bg-background-removal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/poof-bg/openapi/poof-bg-background-removal-api-openapi.yml
claim_count: 1
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
  - summary: Personal data without legal basis
    text: Process personal data without a valid legal basis
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
name: poof-bg
provenance_date: '2026-11-10'
provider_name: poof-bg
provider_slug: poof-bg
slug: poof-bg-eligibility
source_date: '2026-11-10'
source_filename: poof-bg-eligibility.yml
source_heading: Eligibility
source_page: https://poof.bg/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: poof-bg\naid: poof-bg\nurl: https://poof.bg/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal data without legal basis\n  text: Process personal data without a valid legal basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/poof-bg/eligibility/poof-bg-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from poof-bg's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Background Removal
- Image Processing
- Video Processing
---
