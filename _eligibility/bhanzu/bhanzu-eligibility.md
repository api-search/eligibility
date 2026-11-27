---
api_specs:
- filename: bhanzu-ai-api-openapi.yml
  format: yaml
  label: Bhanzu AI API
  slug: bhanzu-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bhanzu/openapi/bhanzu-ai-api-openapi.yml
- filename: bhanzu-content-api-openapi.yml
  format: yaml
  label: Bhanzu Content API
  slug: bhanzu-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bhanzu/openapi/bhanzu-content-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A User above the age of 18 can register on the Platform for itself or a Parent shall register to access and avail the Services for a Student.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: This license is limited to personal and non-commercial uses by You.
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
name: Bhanzu
provenance_date: '2026-11-09'
provider_name: Bhanzu
provider_slug: bhanzu
slug: bhanzu-eligibility
source_date: '2026-11-09'
source_filename: bhanzu-eligibility.yml
source_heading: Eligibility
source_page: https://bhanzu.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bhanzu\naid: bhanzu\nurl: https://bhanzu.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A User above the age of 18 can register on the Platform for itself or a Parent shall register to access\n    and avail the Services for a Student.\nrestricted_uses:\n- summary: No commercial use\n  text: This license is limited to personal and non-commercial uses by You.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bhanzu/eligibility/bhanzu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Bhanzu's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Math
- E-Learning
- Artificial Intelligence
- K-12
---
