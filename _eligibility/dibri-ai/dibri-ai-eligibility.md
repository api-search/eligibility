---
api_specs:
- filename: dibri-ai-openapi-generated.yml
  format: yaml
  label: Dibri API
  slug: dibri-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dibri-ai/openapi/_ae-authored/dibri-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for an organization, you agree to these Terms on its behalf and confirm you have authority to do so; "you" then means that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Safety-critical and high-stakes decisions
    text: Don't rely on the Service as the only basis for legal, medical, financial or safety-critical decisions.
  - summary: Use where failure could cause harm
    text: use the Service where a failure could lead to death, injury or serious damage
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
name: Dibri
provenance_date: '2026-11-09'
provider_name: Dibri
provider_slug: dibri-ai
slug: dibri-ai-eligibility
source_date: '2026-11-09'
source_filename: dibri-ai-eligibility.yml
source_heading: Eligibility
source_page: https://dibri.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dibri\naid: dibri-ai\nurl: https://dibri.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for an organization, you agree to these Terms on its behalf and confirm you have\n    authority to do so; \"you\" then means that organization.\nrestricted_uses:\n- summary: Safety-critical and high-stakes decisions\n  text: Don't rely on the Service as the only basis for legal, medical, financial or safety-critical decisions.\n- summary: Use where failure could cause harm\n  text: use the Service where a failure could\
  \ lead to death, injury or serious damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/dibri-ai/eligibility/dibri-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dibri's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Knowledge Base
- RAG
- Customer Service
- MCP
- REST API
---
