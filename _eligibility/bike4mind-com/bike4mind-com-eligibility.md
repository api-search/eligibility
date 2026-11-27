---
api_specs:
- filename: bike4mind-com-openapi.json
  format: json
  label: Bike4Mind API
  slug: bike4mind-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bike4mind-com/openapi/bike4mind-com-openapi.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use our services.
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
name: Bike4Mind
provenance_date: '2026-11-09'
provider_name: Bike4Mind
provider_slug: bike4mind-com
slug: bike4mind-com-eligibility
source_date: '2026-11-09'
source_filename: bike4mind-com-eligibility.yml
source_heading: Eligibility
source_page: https://bike4mind.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bike4Mind\naid: bike4mind-com\nurl: https://bike4mind.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our services.\n"
source_yaml_url: https://artifacts.apis.io/bike4mind-com/eligibility/bike4mind-com-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Bike4Mind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Open Source
- Platform
- Workbench
---
