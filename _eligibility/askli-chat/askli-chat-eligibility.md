---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Highly sensitive data
    text: Do not use Askli to collect passwords, payment credentials, health records, children's data, regulated financial information, or other highly sensitive information requiring specialized compliance handling unless Askli has explicitly approved that use.
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
name: Askli
provenance_date: '2026-11-09'
provider_name: Askli
provider_slug: askli-chat
slug: askli-chat-eligibility
source_date: '2026-11-09'
source_filename: askli-chat-eligibility.yml
source_heading: Eligibility
source_page: https://www.askli.chat/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Askli\naid: askli-chat\nurl: https://www.askli.chat/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Highly sensitive data\n  text: Do not use Askli to collect passwords, payment credentials, health records, children's data, regulated financial\n    information, or other highly sensitive information requiring specialized compliance handling unless Askli has\n    explicitly approved that use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/askli-chat/eligibility/askli-chat-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Askli's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- User Research
- Market Validation
- Product Development
- Software-as-a-Service
---
