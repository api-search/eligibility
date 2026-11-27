---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Registry.
    type: individual
  - text: If you use the Registry for an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Registry.
    value: '13'
  restricted_uses:
  - summary: No paid services in current code
    text: The current Registry code does not include payments, subscriptions, or paid plans.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may require email verification, approval, invitations, or security checks before allowing some actions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pinokio
provenance_date: '2026-11-10'
provider_name: Pinokio
provider_slug: pinokio-computer
slug: pinokio-computer-eligibility
source_date: '2026-11-10'
source_filename: pinokio-computer-eligibility.yml
source_heading: Eligibility
source_page: https://pinokio.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pinokio\naid: pinokio-computer\nurl: https://pinokio.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Registry.\n- type: business\n  text: If you use the Registry for an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: No paid services in current code\n  text: The current Registry code does not include payments, subscriptions, or paid plans.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We\
  \ may require email verification, approval, invitations, or security checks before allowing some actions.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Registry.\n"
source_yaml_url: https://artifacts.apis.io/pinokio-computer/eligibility/pinokio-computer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Pinokio's own page on 2026-11-10.
synthetic: false
tags:
- AI Launcher
- AI Browser
- Local AI
- Open Source
- Desktop Application
- Script Runner
- One-Click Install
- Image Generation
- Video Generation
- LLM
- Text-to-Speech
- Voice Cloning
- Hugging Face
- Llama
- Discover Directory
- JSON Scripting
---
