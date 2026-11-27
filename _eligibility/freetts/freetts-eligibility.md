---
claim_count: 3
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
  - summary: Hate speech, threats or violence
    text: Generate hate speech, threats, or content promoting violence
  - summary: Spam, harassment or abuse
    text: Use the service to spam, harass, or abuse others
  - summary: Illegal activities
    text: Use the service for illegal activities
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
name: FreeTTS
provenance_date: '2026-11-09'
provider_name: FreeTTS
provider_slug: freetts
slug: freetts-eligibility
source_date: '2026-11-09'
source_filename: freetts-eligibility.yml
source_heading: Eligibility
source_page: https://freetts.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FreeTTS\naid: freetts\nurl: https://freetts.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Hate speech, threats or violence\n  text: Generate hate speech, threats, or content promoting violence\n- summary: Spam, harassment or abuse\n  text: Use the service to spam, harass, or abuse others\n- summary: Illegal activities\n  text: Use the service for illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/freetts/eligibility/freetts-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 3 quoted statements, read from FreeTTS's own page on 2026-11-09.
synthetic: false
tags:
- Text-to-Speech
- Speech Synthesis
- AI-voice
- Audio
- Media
- Accessibility
- Speech-to-Text
- Content Creation
- Developer Tools
---
