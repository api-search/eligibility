---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years or older to use the Services and we do not accept use by younger Members.
    type: individual
  minimum_age:
    text: You must be 18 years or older to use the Services and we do not accept use by younger Members.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You represent and warrant that you will use and access the Services only in accordance with the Terms and the applicable law.
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
name: Bible Chat
provenance_date: '2026-11-09'
provider_name: Bible Chat
provider_slug: bible-chat
slug: bible-chat-eligibility
source_date: '2026-11-09'
source_filename: bible-chat-eligibility.yml
source_heading: Eligibility
source_page: https://thebiblechat.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bible Chat\naid: bible-chat\nurl: https://thebiblechat.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years or older to use the Services and we do not accept use by younger Members.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You represent and warrant that you will use and access the Services only in accordance with the Terms and\n    the applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You must be 18 years or older to use the Services and we do not accept use by younger Members.\n"
source_yaml_url: https://artifacts.apis.io/bible-chat/eligibility/bible-chat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bible Chat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Bible
- Christianity
- Faith
- Artificial Intelligence
- Mobile App
- Spirituality
---
