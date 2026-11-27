---
api_specs:
- filename: registrum-co-uk-openapi.json
  format: json
  label: Registrum API
  slug: registrum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/registrum-co-uk/openapi/registrum-co-uk-openapi.json
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
  - summary: Contacting or profiling individuals
    text: Do not use it to contact, profile or track individuals in ways they would not reasonably expect from a public register entry.
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
name: registrum-co-uk
provenance_date: '2026-11-10'
provider_name: registrum-co-uk
provider_slug: registrum-co-uk
slug: registrum-co-uk-eligibility
source_date: '2026-11-10'
source_filename: registrum-co-uk-eligibility.yml
source_heading: Eligibility
source_page: https://registrum.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: registrum-co-uk\naid: registrum-co-uk\nurl: https://registrum.co.uk/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Contacting or profiling individuals\n  text: Do not use it to contact, profile or track individuals in ways they would not reasonably expect from a public\n    register entry.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/registrum-co-uk/eligibility/registrum-co-uk-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from registrum-co-uk's own page on 2026-11-10.
synthetic: false
tags:
- Companies House
- Financial Data
- JSON:API
- United Kingdom
- Business Intelligence
---
