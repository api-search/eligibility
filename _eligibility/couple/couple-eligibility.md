---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are of the legal age in the jurisdiction of your place of domicile to form a binding contract with us
    type: individual
  minimum_age:
    text: You are of the legal age in the jurisdiction of your place of domicile to form a binding contract with us
    value: null
  restricted_uses:
  - summary: Illegal, offensive or criminal use
    text: You will not use the APP to achieve illegal ends, to offend others, or to commit a misdemeanor, felony, or crime;
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
name: couple
provenance_date: '2026-11-09'
provider_name: couple
provider_slug: couple
slug: couple-eligibility
source_date: '2026-11-09'
source_filename: couple-eligibility.yml
source_heading: Eligibility
source_page: https://couple.me/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: couple\naid: couple\nurl: https://couple.me/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are of the legal age in the jurisdiction of your place of domicile to form a binding contract with us\nrestricted_uses:\n- summary: Illegal, offensive or criminal use\n  text: You will not use the APP to achieve illegal ends, to offend others, or to commit a misdemeanor, felony,\n    or crime;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You are of\
  \ the legal age in the jurisdiction of your place of domicile to form a binding contract with us\n"
source_yaml_url: https://artifacts.apis.io/couple/eligibility/couple-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from couple's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Companion
- Chatbots
- Conversational AI
- Consumer
- Entertainment
---
