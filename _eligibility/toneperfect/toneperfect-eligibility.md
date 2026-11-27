---
api_specs:
- filename: toneperfect-assessment-api-openapi.yml
  format: yaml
  label: TonePerfect (Pronunciation Assessment API) Assessment API
  slug: toneperfect-assessment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toneperfect/openapi/toneperfect-assessment-api-openapi.yml
- filename: toneperfect-capabilities-api-openapi.yml
  format: yaml
  label: TonePerfect (Pronunciation Assessment API) Capabilities API
  slug: toneperfect-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toneperfect/openapi/toneperfect-capabilities-api-openapi.yml
- filename: toneperfect-utilities-api-openapi.yml
  format: yaml
  label: TonePerfect (Pronunciation Assessment API) Utilities API
  slug: toneperfect-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toneperfect/openapi/toneperfect-utilities-api-openapi.yml
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
  - summary: No identification, origin inference or surveillance
    text: Do not use the API to identify people, infer their origin or nationality, or for surveillance
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to use the API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TonePerfect (Pronunciation Assessment API)
provenance_date: '2026-11-10'
provider_name: TonePerfect (Pronunciation Assessment API)
provider_slug: toneperfect
slug: toneperfect-eligibility
source_date: '2026-11-10'
source_filename: toneperfect-eligibility.yml
source_heading: Eligibility
source_page: https://api.toneperfect.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TonePerfect (Pronunciation Assessment API)\naid: toneperfect\nurl: https://api.toneperfect.app/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No identification, origin inference or surveillance\n  text: Do not use the API to identify people, infer their origin or nationality, or for surveillance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account to use the API.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/toneperfect/eligibility/toneperfect-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from TonePerfect (Pronunciation Assessment API)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Speech
- Language Learning
- Pronunciation
---
