---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind that entity to these Terms.
    type: business
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
name: Zatanna
provenance_date: '2026-11-10'
provider_name: Zatanna
provider_slug: zatanna
slug: zatanna-eligibility
source_date: '2026-11-10'
source_filename: zatanna-eligibility.yml
source_heading: Eligibility
source_page: https://www.zatanna.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zatanna\naid: zatanna\nurl: https://www.zatanna.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind that entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zatanna/eligibility/zatanna-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Zatanna's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Integration
- Reverse Engineering
- Automation
- OAuth
- Y Combinator
- Authentication
---
