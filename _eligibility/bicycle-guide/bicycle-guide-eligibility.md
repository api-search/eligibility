---
api_specs:
- filename: bicycle-guide-guide-registry-api-openapi.yml
  format: yaml
  label: Bicycle Guide Guide Registry API
  slug: bicycle-guide-guide-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bicycle-guide/openapi/bicycle-guide-guide-registry-api-openapi.yml
claim_count: 3
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
  restricted_uses:
  - summary: Not professional advice
    text: They are educational material, not professional advice
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
name: Bicycle Guide
provenance_date: '2026-11-09'
provider_name: Bicycle Guide
provider_slug: bicycle-guide
slug: bicycle-guide-eligibility
source_date: '2026-11-09'
source_filename: bicycle-guide-eligibility.yml
source_heading: Eligibility
source_page: https://bicycle.guide/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bicycle Guide\naid: bicycle-guide\nurl: https://bicycle.guide/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your personal use\nrestricted_uses:\n- summary: Not professional advice\n  text: They are educational material, not professional advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts are free and sign in by magic link.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bicycle-guide/eligibility/bicycle-guide-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Bicycle Guide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Guides
- Artificial Intelligence
- Education
- Library
---
