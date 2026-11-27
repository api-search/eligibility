---
api_specs:
- filename: getwebup-v1-openapi.json
  format: json
  label: Getwebup Cloud API V1 API
  slug: getwebup-cloud-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getwebup/openapi/_original/getwebup-v1-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old and capable of forming a binding contract.
    type: individual
  minimum_age:
    text: You are at least 18 years old and capable of forming a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited purposes
    text: You will not use our services for any unlawful or prohibited purpose.
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
name: Getwebup
provenance_date: '2026-11-09'
provider_name: Getwebup
provider_slug: getwebup
slug: getwebup-eligibility
source_date: '2026-11-09'
source_filename: getwebup-eligibility.yml
source_heading: Eligibility
source_page: https://www.getwebup.in/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Getwebup\naid: getwebup\nurl: https://www.getwebup.in/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old and capable of forming a binding contract.\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: You will not use our services for any unlawful or prohibited purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/getwebup/eligibility/getwebup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Getwebup's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
