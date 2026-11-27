---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Platform.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Platform.
    value: '18'
  restricted_uses:
  - summary: No illegal activity or spam
    text: You are not allowed to use our Platform to engage in any kind of conduct that violates any applicable federal, state, local, or international law or regulation
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
name: Hello Audio
provenance_date: '2026-11-09'
provider_name: Hello Audio
provider_slug: hello-audio
slug: hello-audio-eligibility
source_date: '2026-11-09'
source_filename: hello-audio-eligibility.yml
source_heading: Eligibility
source_page: https://helloaudio.fm/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hello Audio\naid: hello-audio\nurl: https://helloaudio.fm/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Platform.\nrestricted_uses:\n- summary: No illegal activity or spam\n  text: You are not allowed to use our Platform to engage in any kind of conduct that violates any applicable federal,\n    state, local, or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/hello-audio/eligibility/hello-audio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hello Audio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Audio
- Podcasts
- Software-as-a-Service
- Private
- Private Podcasts
- Webhook
- Zapier
- Creator Economy
---
