---
api_specs:
- filename: commandplusk-cmdk-api-openapi.yml
  format: yaml
  label: CMD+K Cmdk API
  slug: commandplusk-cmdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commandplusk/openapi/commandplusk-cmdk-api-openapi.yml
- filename: commandplusk-models-api-openapi.yml
  format: yaml
  label: CMD+K Models API
  slug: commandplusk-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commandplusk/openapi/commandplusk-models-api-openapi.yml
- filename: commandplusk-public-api-openapi.yml
  format: yaml
  label: CMD+K Public API
  slug: commandplusk-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commandplusk/openapi/commandplusk-public-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 to use the service.
    value: '16'
  restricted_uses:
  - summary: No medical, legal or high-stakes advice reliance
    text: Don’t rely on the service for medical, legal, or other high-stakes advice.
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
name: CMD+K
provenance_date: '2026-11-09'
provider_name: CMD+K
provider_slug: commandplusk
slug: commandplusk-eligibility
source_date: '2026-11-09'
source_filename: commandplusk-eligibility.yml
source_heading: Eligibility
source_page: https://commandplusk.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CMD+K\naid: commandplusk\nurl: https://commandplusk.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No medical, legal or high-stakes advice reliance\n  text: Don’t rely on the service for medical, legal, or other high-stakes advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 to use the service.\n"
source_yaml_url: https://artifacts.apis.io/commandplusk/eligibility/commandplusk-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CMD+K's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Assistant
- Platform
- Software-as-a-Service
- Developers
---
