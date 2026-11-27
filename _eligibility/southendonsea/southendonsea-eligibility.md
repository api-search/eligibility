---
api_specs:
- filename: southendonsea-southend-now-api-openapi.yml
  format: yaml
  label: SouthendOnSea.city Southend Now API
  slug: southendonsea-southend-now-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/southendonsea/openapi/southendonsea-southend-now-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: SouthendOnSea.city is a local information and community-participation platform serving Southend-on-Sea, Essex.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Submission rules
    text: Submissions may be declined, edited for clarity with the facts preserved, held for evidence or removed when they breach these rules.
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
name: SouthendOnSea.city
provenance_date: '2026-11-10'
provider_name: SouthendOnSea.city
provider_slug: southendonsea
slug: southendonsea-eligibility
source_date: '2026-11-10'
source_filename: southendonsea-eligibility.yml
source_heading: Eligibility
source_page: https://southendonsea.city/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SouthendOnSea.city\naid: southendonsea\nurl: https://southendonsea.city/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: SouthendOnSea.city is a local information and community-participation platform serving Southend-on-Sea,\n    Essex.\nentity_types: []\nrestricted_uses:\n- summary: Submission rules\n  text: Submissions may be declined, edited for clarity with the facts preserved, held for evidence or removed when\n    they breach these rules.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/southendonsea/eligibility/southendonsea-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from SouthendOnSea.city's own page on 2026-11-10.
synthetic: false
tags:
- Open Data
- Southend-on-Sea
- Weather
- Environment
- local data
---
