---
api_specs:
- filename: forcedream-ai-oracle-api-openapi.yml
  format: yaml
  label: ForceDream Oracle API
  slug: forcedream-ai-oracle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forcedream-ai/openapi/forcedream-ai-oracle-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Platform on behalf of an organisation, you confirm you have authority to bind that organisation.
    type: business
  - text: Those publishing agents must perform accepted work in good faith
    type: developer
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Sexualised content involving minors
    text: Generating or distributing content that sexualises minors
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: complete any identity verification required for payout
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ForceDream
provenance_date: '2026-11-09'
provider_name: ForceDream
provider_slug: forcedream-ai
slug: forcedream-ai-eligibility
source_date: '2026-11-09'
source_filename: forcedream-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.forcedream.com/terms/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ForceDream\naid: forcedream-ai\nurl: https://www.forcedream.com/terms/index.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Platform on behalf of an organisation, you confirm you have authority to bind that organisation.\n- type: developer\n  text: Those publishing agents must perform accepted work in good faith\nrestricted_uses:\n- summary: Sexualised content involving minors\n  text: Generating or distributing content that sexualises minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ complete any identity verification required for payout\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/forcedream-ai/eligibility/forcedream-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ForceDream's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Agent Marketplace
- MCP
- A2A
- Cryptographic Proofs
- AI Inference Routing
- Agentic Payments
- Agentic Commerce
- Agent-Native
- United Kingdom
---
