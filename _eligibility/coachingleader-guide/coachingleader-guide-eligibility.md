---
api_specs:
- filename: coachingleader-guide-openapi.yml
  format: yaml
  label: Bicycle Guide Guide Registry API
  slug: guide-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coachingleader-guide/openapi/coachingleader-guide-openapi.yml
claim_count: 2
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
    text: Accounts are free and sign in by magic link.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coaching Leader Guide
provenance_date: '2026-11-09'
provider_name: Coaching Leader Guide
provider_slug: coachingleader-guide
slug: coachingleader-guide-eligibility
source_date: '2026-11-09'
source_filename: coachingleader-guide-eligibility.yml
source_heading: Eligibility
source_page: https://coachingleader.guide/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coaching Leader Guide\naid: coachingleader-guide\nurl: https://coachingleader.guide/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your personal use\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts are free and sign in by magic link.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coachingleader-guide/eligibility/coachingleader-guide-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Coaching Leader Guide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coaching
- Leadership
- Management
- Education
- Books
- MCP
---
