---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Website, you represent that you are at least 18 years old and have the legal capacity to agree to these Terms.
    type: individual
  minimum_age:
    text: By using the Website, you represent that you are at least 18 years old and have the legal capacity to agree to these Terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use the Website for any unlawful, fraudulent, deceptive, or harmful purpose, or in violation of any applicable law or regulation.
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
name: AgentSmyth
provenance_date: '2026-11-09'
provider_name: AgentSmyth
provider_slug: agentsmyth
slug: agentsmyth-eligibility
source_date: '2026-11-09'
source_filename: agentsmyth-eligibility.yml
source_heading: Eligibility
source_page: https://agentsmyth.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentSmyth\naid: agentsmyth\nurl: https://agentsmyth.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Website, you represent that you are at least 18 years old and have the legal capacity to agree\n    to these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: use the Website for any unlawful, fraudulent, deceptive, or harmful purpose, or in violation of any applicable\n    law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: By using the Website, you represent that you are at least 18 years old and have the legal capacity to agree\n    to these Terms.\n"
source_yaml_url: https://artifacts.apis.io/agentsmyth/eligibility/agentsmyth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AgentSmyth's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Capital Markets
- Artificial Intelligence
- AI Agents
- Trading
- Investment Research
- Market Intelligence
- MCP
- Agent-Native
- Fintech
---
