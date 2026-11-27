---
api_specs:
- filename: aopx-fr-aopx-recommend-v0-api-openapi.yml
  format: yaml
  label: aopx-fr AOPX Recommend v0 API
  slug: aopx-fr-aopx-recommend-v0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aopx-fr/openapi/aopx-fr-aopx-recommend-v0-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: AOPX does not require a public user account for the current pilot
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: aopx-fr
provenance_date: '2026-11-09'
provider_name: aopx-fr
provider_slug: aopx-fr
slug: aopx-fr-eligibility
source_date: '2026-11-09'
source_filename: aopx-fr-eligibility.yml
source_heading: Eligibility
source_page: https://aopx.fr/legals.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aopx-fr\naid: aopx-fr\nurl: https://aopx.fr/legals.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: AOPX does not require a public user account for the current pilot\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aopx-fr/eligibility/aopx-fr-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from aopx-fr's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Artificial Intelligence
- Routing
- Benchmarks
- Evidence
---
