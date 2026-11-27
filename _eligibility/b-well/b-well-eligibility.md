---
api_specs:
- filename: b-well-users-api-openapi.yml
  format: yaml
  label: b.well Users API
  slug: b-well-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/b-well/openapi/b-well-users-api-openapi.yml
- filename: b-well-webhook-api-openapi.yml
  format: yaml
  label: b.well Webhook API
  slug: b-well-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/b-well/openapi/b-well-webhook-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Account login credentials ( “credentials” ) issued to you by us are intended to be used only by you in your individual or personal representative capacity.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal, noncommercial use only
    text: Use the b.well application for anything but your personal, noncommercial use;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To access the b.well application, you will need to register for an account, and complete appropriate identity verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: b.well
provenance_date: '2026-11-09'
provider_name: b.well
provider_slug: b-well
slug: b-well-eligibility
source_date: '2026-11-09'
source_filename: b-well-eligibility.yml
source_heading: Eligibility
source_page: https://www.icanbwell.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: b.well\naid: b-well\nurl: https://www.icanbwell.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Account login credentials ( “credentials” ) issued to you by us are intended to be used only by you in your\n    individual or personal representative capacity.\nrestricted_uses:\n- summary: Personal, noncommercial use only\n  text: Use the b.well application for anything but your personal, noncommercial use;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To access the b.well application,\
  \ you will need to register for an account, and complete appropriate identity\n    verification.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/b-well/eligibility/b-well-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from b.well's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- FHIR
- Health Data
- Interoperability
- Patient Access
- Health Records
- MCP
---
