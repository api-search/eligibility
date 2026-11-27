---
api_specs:
- filename: propexo-openapi-generated.yml
  format: yaml
  label: Propexo API
  slug: propexo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propexo/openapi/_ae-authored/propexo-openapi-generated.yml
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
  - summary: Competing product development
    text: (g) access or use the Propexo Solution to build a similar or competitive product or service
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
name: Propexo
provenance_date: '2026-11-10'
provider_name: Propexo
provider_slug: propexo
slug: propexo-eligibility
source_date: '2026-11-10'
source_filename: propexo-eligibility.yml
source_heading: Eligibility
source_page: https://propexo.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Propexo\naid: propexo\nurl: https://propexo.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competing product development\n  text: (g) access or use the Propexo Solution to build a similar or competitive product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/propexo/eligibility/propexo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Propexo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data Platform
- Integration
- PropTech
---
