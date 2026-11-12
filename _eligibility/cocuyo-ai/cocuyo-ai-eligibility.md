---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old. All of Cocuyo—the catalog and the Studio—is for adults
    type: individual
  minimum_age:
    text: Be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful activity
    text: Use Create for illegal activities, fraud, harassment, threats, exploitation, abuse, or to harm other people.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you confirm this when creating your account or subscribing to a plan
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cocuyo
provenance_date: '2026-11-09'
provider_name: Cocuyo
provider_slug: cocuyo-ai
slug: cocuyo-ai-eligibility
source_date: '2026-11-09'
source_filename: cocuyo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cocuyo.ai/en/terminos.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cocuyo\naid: cocuyo-ai\nurl: https://cocuyo.ai/en/terminos.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old. All of Cocuyo—the catalog and the Studio—is for adults\nrestricted_uses:\n- summary: Illegal or harmful activity\n  text: Use Create for illegal activities, fraud, harassment, threats, exploitation, abuse, or to harm other people.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you confirm this when creating your account or subscribing to a plan\nminimum_age:\n  value:\
  \ '18'\n  text: Be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/cocuyo-ai/eligibility/cocuyo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cocuyo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Image Generation
- Video Generation
- Text To Speech
- MCP
- Creative Tools
---
