---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human. Accounts registered by "bots" or other automated methods are not permitted.
    type: individual
  - text: When we say "You" or "your", we are referring to the people or organizations that own an account with one or more of our Services.
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
name: AdMakeAI
provenance_date: '2026-11-09'
provider_name: AdMakeAI
provider_slug: admakeai
slug: admakeai-eligibility
source_date: '2026-11-09'
source_filename: admakeai-eligibility.yml
source_heading: Eligibility
source_page: https://admakeai.com/resources/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdMakeAI\naid: admakeai\nurl: https://admakeai.com/resources/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human. Accounts registered by \"bots\" or other automated methods are not permitted.\n- type: business\n  text: When we say \"You\" or \"your\", we are referring to the people or organizations that own an account with one\n    or more of our Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/admakeai/eligibility/admakeai-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from AdMakeAI's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Marketing
- AdTech
- Generative AI
- Image Generation
- Video Generation
- Meta Ads
- Competitive Intelligence
- MCP
- Agents
- Agent Skills
---
