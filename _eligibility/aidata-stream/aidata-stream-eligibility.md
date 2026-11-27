---
api_specs:
- filename: aidata-stream-openapi-generated.yml
  format: yaml
  label: aidata-stream API
  slug: aidata-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aidata-stream/openapi/_ae-authored/aidata-stream-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be at least 16 years of age
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful use
    text: Use the Service to harm, harass, or defraud others
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
name: aidata-stream
provenance_date: '2026-11-09'
provider_name: aidata-stream
provider_slug: aidata-stream
slug: aidata-stream-eligibility
source_date: '2026-11-09'
source_filename: aidata-stream-eligibility.yml
source_heading: Eligibility
source_page: https://aidata.stream/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aidata-stream\naid: aidata-stream\nurl: https://aidata.stream/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Use the Service to harm, harass, or defraud others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Be at least 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/aidata-stream/eligibility/aidata-stream-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from aidata-stream's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Analytics
- SEO
- Marketing
- Data
---
