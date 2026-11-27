---
api_specs:
- filename: meshes-openapi-generated.yml
  format: yaml
  label: Meshes API
  slug: meshes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meshes/openapi/_ae-authored/meshes-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is offered and available to users who are 18 years of age or older.
    type: individual
  - text: Confirm that you are at least 18 years old and have the authority to enter into this contract on behalf of yourself or the organization you represent.
    type: business
  minimum_age:
    text: The Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Compliance with laws and Acceptable Use Policy
    text: You must comply with all of the terms and conditions of this Terms of Service, our Acceptable Use Policy, and all applicable laws, regulations, and rules when you use the Website and our Services.
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
name: Meshes
provenance_date: '2026-11-10'
provider_name: Meshes
provider_slug: meshes
slug: meshes-eligibility
source_date: '2026-11-10'
source_filename: meshes-eligibility.yml
source_heading: Eligibility
source_page: https://meshes.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meshes\naid: meshes\nurl: https://meshes.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is offered and available to users who are 18 years of age or older.\n- type: business\n  text: Confirm that you are at least 18 years old and have the authority to enter into this contract on behalf\n    of yourself or the organization you represent.\nrestricted_uses:\n- summary: Compliance with laws and Acceptable Use Policy\n  text: You must comply with all of the terms and conditions of this Terms of Service,\
  \ our Acceptable Use Policy,\n    and all applicable laws, regulations, and rules when you use the Website and our Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/meshes/eligibility/meshes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Meshes's own page on 2026-11-10.
synthetic: false
tags:
- Company
- iPaaS
- Software-as-a-Service
- Integration
---
