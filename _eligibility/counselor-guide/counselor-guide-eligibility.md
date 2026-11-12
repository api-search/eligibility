---
api_specs:
- filename: counselor-guide-openapi.yml
  format: yaml
  label: Bicycle Guide Registry API
  slug: guide-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counselor-guide/openapi/counselor-guide-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your personal use
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Counselor Guide
provenance_date: '2026-11-09'
provider_name: Counselor Guide
provider_slug: counselor-guide
slug: counselor-guide-eligibility
source_date: '2026-11-09'
source_filename: counselor-guide-eligibility.yml
source_heading: Eligibility
source_page: https://counselor.guide/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Counselor Guide\naid: counselor-guide\nurl: https://counselor.guide/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your personal use\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/counselor-guide/eligibility/counselor-guide-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Counselor Guide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Counseling
- Psychotherapy
- Mental Health
- Education
- Professional Development
- Books
- MCP
---
