---
api_specs:
- filename: bugtape-ai-openapi-generated.yml
  format: yaml
  label: BugTape API
  slug: bugtape-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bugtape-ai/openapi/_ae-authored/bugtape-ai-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Anyone can sign up and start on the Free plan.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: BugTape
provenance_date: '2026-11-09'
provider_name: BugTape
provider_slug: bugtape-ai
slug: bugtape-ai-eligibility
source_date: '2026-11-09'
source_filename: bugtape-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bugtape.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BugTape\naid: bugtape-ai\nurl: https://bugtape.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Anyone can sign up and start on the Free plan.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bugtape-ai/eligibility/bugtape-ai-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from BugTape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Error Tracking
- AI Agents
- Developer Tools
- Software-as-a-Service
---
