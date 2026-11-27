---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to create an account.
    value: '13'
  restricted_uses:
  - summary: Chat restricted to 18+
    text: Chat is 18+. If you are under 18 you can browse characters, build your own characters, and take courses, but you cannot send messages to an AI character
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
name: AI Anyone
provenance_date: '2026-11-09'
provider_name: AI Anyone
provider_slug: aianyone-com
slug: aianyone-com-eligibility
source_date: '2026-11-09'
source_filename: aianyone-com-eligibility.yml
source_heading: Eligibility
source_page: https://aianyone.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Anyone\naid: aianyone-com\nurl: https://aianyone.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Chat restricted to 18+\n  text: Chat is 18+. If you are under 18 you can browse characters, build your own characters, and take courses,\n    but you cannot send messages to an AI character\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/aianyone-com/eligibility/aianyone-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from AI Anyone's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- Voice
- Education
- Platform
---
