---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human. Accounts registered by “bots” or other automated methods are not permitted.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal use
    text: You may not use the Service for any illegal purpose or to violate any laws in your jurisdiction (including but not limited to copyright laws).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alice
provenance_date: '2026-11-09'
provider_name: Alice
provider_slug: aliceapp-ai
slug: aliceapp-ai-eligibility
source_date: '2026-11-09'
source_filename: aliceapp-ai-eligibility.yml
source_heading: Eligibility
source_page: https://aliceapp.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alice\naid: aliceapp-ai\nurl: https://aliceapp.ai/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human. Accounts registered by “bots” or other automated methods are not permitted.\nrestricted_uses:\n- summary: No illegal use\n  text: You may not use the Service for any illegal purpose or to violate any laws in your jurisdiction (including\n    but not limited to copyright laws).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address, and any other information\
  \ requested in order to complete the signup\n    process.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aliceapp-ai/eligibility/aliceapp-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Alice's own page on 2026-11-09.
synthetic: false
tags:
- Audio
- Transcription
- Artificial Intelligence
- Privacy
- Healthcare
---
