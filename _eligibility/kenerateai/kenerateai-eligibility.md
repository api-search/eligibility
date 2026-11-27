---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old, or the minimum age required in your country, to use Kenerate AI.
    type: individual
  minimum_age:
    text: You must be at least 13 years old, or the minimum age required in your country, to use Kenerate AI.
    value: '13'
  restricted_uses:
  - summary: Child sexual abuse material
    text: Generating, requesting, uploading, or attempting to create any Child Sexual Abuse Material (CSAM), or any content that exploits or endangers minors will result in an IMMEDIATE & PERMANENT ACCOUNT BLOCK / TERMINATION (ID BAN) with zero refund
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
name: Kenerate AI
provenance_date: '2026-11-09'
provider_name: Kenerate AI
provider_slug: kenerateai
slug: kenerateai-eligibility
source_date: '2026-11-09'
source_filename: kenerateai-eligibility.yml
source_heading: Eligibility
source_page: https://kenerateai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kenerate AI\naid: kenerateai\nurl: https://kenerateai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old, or the minimum age required in your country, to use Kenerate AI.\nrestricted_uses:\n- summary: Child sexual abuse material\n  text: Generating, requesting, uploading, or attempting to create any Child Sexual Abuse Material (CSAM), or any\n    content that exploits or endangers minors will result in an IMMEDIATE & PERMANENT ACCOUNT BLOCK / TERMINATION\n    (ID BAN) with zero refund\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old, or the minimum age required in your country, to use Kenerate AI.\n"
source_yaml_url: https://artifacts.apis.io/kenerateai/eligibility/kenerateai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kenerate AI's own page on 2026-11-09.
synthetic: false
tags:
- AI Generation
- Image Editing
- Video Generation
- Audio Generation
- 3D Content
- Creative Tools
---
