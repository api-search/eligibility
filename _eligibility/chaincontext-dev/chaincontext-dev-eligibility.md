---
api_specs:
- filename: chaincontext-dev-openapi-generated.yml
  format: yaml
  label: ChainContext API
  slug: chaincontext-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaincontext-dev/openapi/_ae-authored/chaincontext-dev-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Money laundering, terror financing, sanctions evasion
    text: Facilitate money laundering, terrorist financing, or sanctions evasion
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
name: ChainContext
provenance_date: '2026-11-09'
provider_name: ChainContext
provider_slug: chaincontext-dev
slug: chaincontext-dev-eligibility
source_date: '2026-11-09'
source_filename: chaincontext-dev-eligibility.yml
source_heading: Eligibility
source_page: https://chaincontext.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChainContext\naid: chaincontext-dev\nurl: https://chaincontext.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Money laundering, terror financing, sanctions evasion\n  text: Facilitate money laundering, terrorist financing, or sanctions evasion\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/chaincontext-dev/eligibility/chaincontext-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ChainContext's own page on 2026-11-09.
synthetic: false
tags:
- MCP Builder
- DeFi
- Governance
- Trading
- Analytics
- Security
- Artificial Intelligence
- Blockchain
---
