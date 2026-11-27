---
api_specs:
- filename: dantelabs-api-openapi.json
  format: json
  label: Dante Labs genome data Api API
  slug: dante-labs-genome-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dantelabs/openapi/_original/dantelabs-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not purchase the Service if ... you are not allowed to receiving the Services under the laws of the jurisdiction in which you are resident or from which you use the Services.
  minimum_age:
    text: if you provide your own genetic information, you must be at least eighteen (18) years old to agree to these TOS on behalf of yourself
    value: '18'
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
name: Dantelabs
provenance_date: '2026-11-09'
provider_name: Dantelabs
provider_slug: dantelabs
slug: dantelabs-eligibility
source_date: '2026-11-09'
source_filename: dantelabs-eligibility.yml
source_heading: Eligibility
source_page: https://dantelabs.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dantelabs\naid: dantelabs\nurl: https://dantelabs.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not purchase the Service if ... you are not allowed to receiving the Services under the laws of\n    the jurisdiction in which you are resident or from which you use the Services.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you provide your own genetic information, you must be at least eighteen (18) years old to agree to these\n    TOS on behalf of yourself\n"
source_yaml_url: https://artifacts.apis.io/dantelabs/eligibility/dantelabs-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Dantelabs's own page on 2026-11-09.
synthetic: false
tags:
- Genomics
- Health
- DNA
- Clinical Testing
- Artificial Intelligence
---
