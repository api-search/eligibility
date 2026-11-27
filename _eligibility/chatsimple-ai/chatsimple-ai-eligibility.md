---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Visitor identification use limited to B2B
    text: You will use the data solely for lawful B2B marketing and sales purposes.
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
provider_slug: chatsimple-ai
slug: chatsimple-ai-eligibility
source_date: '2026-11-09'
source_filename: chatsimple-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.expertise.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chatsimple\naid: chatsimple-ai\nurl: https://www.expertise.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Visitor identification use limited to B2B\n  text: You will use the data solely for lawful B2B marketing and sales purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/chatsimple-ai/eligibility/chatsimple-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Chatsimple's own page on 2026-11-09.
synthetic: false
tags:
- Enterprise AI
- Customer Service
- Multi-Channel
- AI Deployment
---
