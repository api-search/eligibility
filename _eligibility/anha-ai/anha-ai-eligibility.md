---
api_specs:
- filename: anha-ai-openapi-generated.yml
  format: yaml
  label: ANHA Registry API
  slug: anha-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anha-ai/openapi/_ae-authored/anha-ai-openapi-generated.yml
claim_count: 1
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
  - summary: Brand/person impersonation in handles
    text: Registering a handle that impersonates a brand or a person you have no right to represent is not permitted
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
name: ANHA Registry
provenance_date: '2026-11-09'
provider_name: ANHA Registry
provider_slug: anha-ai
slug: anha-ai-eligibility
source_date: '2026-11-09'
source_filename: anha-ai-eligibility.yml
source_heading: Eligibility
source_page: https://anha.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ANHA Registry\naid: anha-ai\nurl: https://anha.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Brand/person impersonation in handles\n  text: Registering a handle that impersonates a brand or a person you have no right to represent is not permitted\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anha-ai/eligibility/anha-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ANHA Registry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Security
- Zero Trust
- Post-Quantum
- Identity
---
