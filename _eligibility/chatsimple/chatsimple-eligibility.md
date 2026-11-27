---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Targeting individuals via enrichment data
    text: Use visitor identification or company enrichment data to identify, stalk, harass, or target individual natural persons
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
name: Chatsimple
provenance_date: '2026-11-09'
provider_name: Chatsimple
provider_slug: chatsimple
slug: chatsimple-eligibility
source_date: '2026-11-09'
source_filename: chatsimple-eligibility.yml
source_heading: Eligibility
source_page: https://www.expertise.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chatsimple\naid: chatsimple\nurl: https://www.expertise.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Targeting individuals via enrichment data\n  text: Use visitor identification or company enrichment data to identify, stalk, harass, or target individual natural\n    persons\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/chatsimple/eligibility/chatsimple-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Chatsimple's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Conversational AI
- Chatbots
- Lead Generation
- Sales Automation
- CRM Integration
- Voice AI
- Go-To-Market
- Customer Engagement
---
