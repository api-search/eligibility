---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least eighteen (18) years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: transmit, distribute, display or otherwise make available through or in connection with the Services any content, including any Customer Data (as defined below), in a manner which infringes third party rights
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
name: Naboo
provenance_date: '2026-11-10'
provider_name: Naboo
provider_slug: naboo
slug: naboo-eligibility
source_date: '2026-11-10'
source_filename: naboo-eligibility.yml
source_heading: Eligibility
source_page: https://www.naboo.ai/terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Naboo\naid: naboo\nurl: https://www.naboo.ai/terms-of-use.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: transmit, distribute, display or otherwise make available through or in connection with the Services any\n    content, including any Customer Data (as defined below), in a manner which infringes third party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to\
  \ use the Services.\n"
source_yaml_url: https://artifacts.apis.io/naboo/eligibility/naboo-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Naboo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Knowledge Graph
- Reasoning Layer
- GraphQL
- MCP
- Enterprise Software
- Developer Infrastructure
- RAG
---
