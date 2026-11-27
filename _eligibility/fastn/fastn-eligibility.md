---
api_specs:
- filename: fastn-openapi-generated.yml
  format: yaml
  label: Fastn API
  slug: fastn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastn/openapi/_ae-authored/fastn-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the services, you must be at least 18 years old and have the legal capacity to enter into this agreement.
    type: individual
  minimum_age:
    text: To use the services, you must be at least 18 years old and have the legal capacity to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorised purposes
    text: 'You may not use the services for any illegal or unauthorised purpose, including but not limited to:'
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
name: Fastn
provenance_date: '2026-11-09'
provider_name: Fastn
provider_slug: fastn
slug: fastn-eligibility
source_date: '2026-11-09'
source_filename: fastn-eligibility.yml
source_heading: Eligibility
source_page: https://fastn.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fastn\naid: fastn\nurl: https://fastn.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the services, you must be at least 18 years old and have the legal capacity to enter into this agreement.\nrestricted_uses:\n- summary: Illegal or unauthorised purposes\n  text: 'You may not use the services for any illegal or unauthorised purpose, including but not limited to:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the services, you must be at\
  \ least 18 years old and have the legal capacity to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/fastn/eligibility/fastn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fastn's own page on 2026-11-09.
synthetic: false
tags:
- Integration Platform
- B2B SaaS
- Embedded Widget
- Unified API
- Data Integration
- AI Agents
- CRM Integration
- Security
---
