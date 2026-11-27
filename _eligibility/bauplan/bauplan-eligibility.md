---
api_specs:
- filename: bauplan-bauplanlabs-api-openapi.yml
  format: yaml
  label: Bauplan Bauplanlabs API
  slug: bauplan-bauplanlabs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bauplan/openapi/bauplan-bauplanlabs-api-openapi.yml
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
  - summary: Non-commercial testing only
    text: You agree to use the Sandbox only for non-commercial purposes and in compliance with applicable laws.
  - summary: No personal, regulated or export-controlled data
    text: use the Sandbox to process personal, regulated, or export-controlled data
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
name: Bauplan
provenance_date: '2026-11-09'
provider_name: Bauplan
provider_slug: bauplan
slug: bauplan-eligibility
source_date: '2026-11-09'
source_filename: bauplan-eligibility.yml
source_heading: Eligibility
source_page: https://bauplanlabs.com/terms-and-conditions-sandbox
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bauplan\naid: bauplan\nurl: https://bauplanlabs.com/terms-and-conditions-sandbox\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial testing only\n  text: You agree to use the Sandbox only for non-commercial purposes and in compliance with applicable laws.\n- summary: No personal, regulated or export-controlled data\n  text: use the Sandbox to process personal, regulated, or export-controlled data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bauplan/eligibility/bauplan-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Bauplan's own page on 2026-11-09.
synthetic: false
tags:
- Data Engineering
- AI Agents
- Serverless Platform
- Data Pipeline
- Data Integration
- Isolation and Rollback
---
