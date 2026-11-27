---
api_specs:
- filename: tohuman-humanizations-api-openapi.yml
  format: yaml
  label: ToHuman Humanizations API
  slug: tohuman-humanizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-humanizations-api-openapi.yml
- filename: tohuman-humanize-api-openapi.yml
  format: yaml
  label: ToHuman Humanize API
  slug: tohuman-humanize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-humanize-api-openapi.yml
- filename: tohuman-submit-api-openapi.yml
  format: yaml
  label: ToHuman Submit API
  slug: tohuman-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-submit-api-openapi.yml
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
  - summary: Illegal or harmful content
    text: Use the Service to generate content that is illegal, harmful, or violates third-party rights
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
name: ToHuman
provenance_date: '2026-11-10'
provider_name: ToHuman
provider_slug: tohuman
slug: tohuman-eligibility
source_date: '2026-11-10'
source_filename: tohuman-eligibility.yml
source_heading: Eligibility
source_page: https://tohuman.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ToHuman\naid: tohuman\nurl: https://tohuman.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Use the Service to generate content that is illegal, harmful, or violates third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tohuman/eligibility/tohuman-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ToHuman's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Text-Humanization
- Content Generation
- Marketing
- Software-as-a-Service
---
