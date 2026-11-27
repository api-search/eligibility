---
api_specs:
- filename: cityparity-com-api-openapi.json
  format: json
  label: cityparity REST API API
  slug: cityparity-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cityparity-com/openapi/_original/cityparity-com-api-openapi.json
claim_count: 2
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
  - summary: Not financial, immigration or tax advice
    text: It is not financial advice, immigration advice, tax advice, or anything you should bet a major life decision on without other research.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: 'There are no accounts: nothing here requires a signup, and a comparison saves into its own URL'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: cityparity
provenance_date: '2026-11-09'
provider_name: cityparity
provider_slug: cityparity-com
slug: cityparity-com-eligibility
source_date: '2026-11-09'
source_filename: cityparity-com-eligibility.yml
source_heading: Eligibility
source_page: https://cityparity.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cityparity\naid: cityparity-com\nurl: https://cityparity.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not financial, immigration or tax advice\n  text: It is not financial advice, immigration advice, tax advice, or anything you should bet a major life decision\n    on without other research.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: 'There are no accounts: nothing here requires a signup, and a comparison saves into its own URL'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cityparity-com/eligibility/cityparity-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from cityparity's own page on 2026-11-09.
synthetic: false
tags:
- Cost of Living
- Comparison Tool
- Data Visualization
- Expatriate Resources
- Financial Planning
---
