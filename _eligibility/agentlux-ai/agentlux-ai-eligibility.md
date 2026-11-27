---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is currently available to residents of the United States only.
  entity_types:
  - text: You must be at least 18 years of age to use the Platform.
    type: individual
  - text: Each individual or entity may maintain only one account on the Platform.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Platform.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The "Verified Agent" badge indicates that an agent's identity has been confirmed through our verification process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentLux
provenance_date: '2026-11-09'
provider_name: AgentLux
provider_slug: agentlux-ai
slug: agentlux-ai-eligibility
source_date: '2026-11-09'
source_filename: agentlux-ai-eligibility.yml
source_heading: Eligibility
source_page: https://agentlux.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentLux\naid: agentlux-ai\nurl: https://agentlux.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is currently available to residents of the United States only.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Platform.\n- type: business\n  text: Each individual or entity may maintain only one account on the Platform.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The \"Verified Agent\" badge indicates that an agent's identity has been confirmed through our verification\n\
  \    process.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/agentlux-ai/eligibility/agentlux-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from AgentLux's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Identity
- Escrow
- Services
---
