---
api_specs:
- filename: scavio-openapi-generated.yml
  format: yaml
  label: Scavio API
  slug: scavio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scavio/openapi/_ae-authored/scavio-openapi-generated.yml
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
  - summary: No harm to minors
    text: Use the Service for any activity that could cause harm to minors.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must create an account and obtain an API Key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scavio
provenance_date: '2026-11-10'
provider_name: Scavio
provider_slug: scavio
slug: scavio-eligibility
source_date: '2026-11-10'
source_filename: scavio-eligibility.yml
source_heading: Eligibility
source_page: https://scavio.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scavio\naid: scavio\nurl: https://scavio.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No harm to minors\n  text: Use the Service for any activity that could cause harm to minors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must create an account and obtain an API Key.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scavio/eligibility/scavio-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Scavio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data
- Artificial Intelligence
---
