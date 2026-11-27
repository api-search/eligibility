---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old and able to form a binding contract where you live.
    type: individual
  - text: If you use avva on behalf of an employer or client, you confirm you are authorized to accept these Terms for them and to disclose the material you submit.
    type: business
  minimum_age:
    text: You must be at least 16 years old and able to form a binding contract where you live.
    value: '16'
  restricted_uses:
  - summary: No regulated professional advice under avva’s name
    text: You must not use avva to provide regulated professional advice under avva’s name.
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
name: avva
provenance_date: '2026-11-09'
provider_name: avva
provider_slug: avva-chat
slug: avva-chat-eligibility
source_date: '2026-11-09'
source_filename: avva-chat-eligibility.yml
source_heading: Eligibility
source_page: https://avva.chat/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: avva\naid: avva-chat\nurl: https://avva.chat/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old and able to form a binding contract where you live.\n- type: business\n  text: If you use avva on behalf of an employer or client, you confirm you are authorized to accept these Terms\n    for them and to disclose the material you submit.\nrestricted_uses:\n- summary: No regulated professional advice under avva’s name\n  text: You must not use avva to provide regulated professional advice under avva’s\
  \ name.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and able to form a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/avva-chat/eligibility/avva-chat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from avva's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- DecisionModel
- Expertise
- Platform
- Barcelona
---
