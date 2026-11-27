---
api_specs:
- filename: mcpifex-openapi-generated.yml
  format: yaml
  label: Amdose API
  slug: mcpifex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpifex/openapi/_ae-authored/mcpifex-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you confirm that you have authority to accept these Terms for it.
    type: business
  minimum_age:
    text: You must provide accurate information and be at least 16 years old, and old enough to form a binding contract where you live.
    value: '16'
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
name: Amdose
provenance_date: '2026-11-10'
provider_name: Amdose
provider_slug: mcpifex
slug: mcpifex-eligibility
source_date: '2026-11-10'
source_filename: mcpifex-eligibility.yml
source_heading: Eligibility
source_page: https://mcpifex.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amdose\naid: mcpifex\nurl: https://mcpifex.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you confirm that you have authority to accept these\n    Terms for it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must provide accurate information and be at least 16 years old, and old enough to form a binding contract\n    where you live.\n"
source_yaml_url: https://artifacts.apis.io/mcpifex/eligibility/mcpifex-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Amdose's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- Marketplace
- AI Agents
- Integration
---
