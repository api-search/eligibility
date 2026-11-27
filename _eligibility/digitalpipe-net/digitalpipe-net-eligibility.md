---
api_specs:
- filename: digitalpipe-net-openapi-generated.yml
  format: yaml
  label: digitalpipe-net API
  slug: digitalpipe-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digitalpipe-net/openapi/_ae-authored/digitalpipe-net-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to create an account
    value: '16'
  restricted_uses:
  - summary: Illegal activity
    text: Use our service to facilitate illegal activities
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
name: digitalpipe-net
provenance_date: '2026-11-09'
provider_name: digitalpipe-net
provider_slug: digitalpipe-net
slug: digitalpipe-net-eligibility
source_date: '2026-11-09'
source_filename: digitalpipe-net-eligibility.yml
source_heading: Eligibility
source_page: https://digitalpipe.net/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: digitalpipe-net\naid: digitalpipe-net\nurl: https://digitalpipe.net/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal activity\n  text: Use our service to facilitate illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account\n"
source_yaml_url: https://artifacts.apis.io/digitalpipe-net/eligibility/digitalpipe-net-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from digitalpipe-net's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- API Management
- Security
- Cloud
---
