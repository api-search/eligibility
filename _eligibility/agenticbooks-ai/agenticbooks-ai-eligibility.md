---
api_specs:
- filename: agenticbooks-ai-openapi-generated.yml
  format: yaml
  label: AgenticBooks API
  slug: agenticbooks-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticbooks-ai/openapi/_ae-authored/agenticbooks-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for business use only
    type: business
  minimum_age:
    text: you confirm that you are at least 18
    value: '18'
  restricted_uses:
  - summary: Business use only
    text: The Service is for business use only
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
name: AgenticBooks
provenance_date: '2026-11-09'
provider_name: AgenticBooks
provider_slug: agenticbooks-ai
slug: agenticbooks-ai-eligibility
source_date: '2026-11-09'
source_filename: agenticbooks-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.agenticbooks.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgenticBooks\naid: agenticbooks-ai\nurl: https://www.agenticbooks.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for business use only\nrestricted_uses:\n- summary: Business use only\n  text: The Service is for business use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18\n"
source_yaml_url: https://artifacts.apis.io/agenticbooks-ai/eligibility/agenticbooks-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AgenticBooks's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Bookkeeping
- Finance
- Automation
- Software-as-a-Service
---
