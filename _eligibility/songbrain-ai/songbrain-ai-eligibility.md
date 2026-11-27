---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may register only if you are at least 16 years old (or older if your local law requires a higher age of digital consent).
    type: individual
  minimum_age:
    text: You may register only if you are at least 16 years old (or older if your local law requires a higher age of digital consent).
    value: '16'
  restricted_uses:
  - summary: Unauthorised audio uploads
    text: upload audio for which you do not hold sufficient rights (e.g. tracks you did not create or are not licensed to distribute for analysis)
  - summary: Misuse of third-party AI music
    text: upload or publish music generated with a third-party AI tool beyond what that tool's licence allows you to do with it
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The sign-up form asks you to confirm that you are 16 or older.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: songbrain-ai
provenance_date: '2026-11-10'
provider_name: songbrain-ai
provider_slug: songbrain-ai
slug: songbrain-ai-eligibility
source_date: '2026-11-10'
source_filename: songbrain-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.songbrain.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: songbrain-ai\naid: songbrain-ai\nurl: https://www.songbrain.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may register only if you are at least 16 years old (or older if your local law requires a higher age\n    of digital consent).\nrestricted_uses:\n- summary: Unauthorised audio uploads\n  text: upload audio for which you do not hold sufficient rights (e.g. tracks you did not create or are not licensed\n    to distribute for analysis)\n- summary: Misuse of third-party AI music\n  text: upload or publish music generated\
  \ with a third-party AI tool beyond what that tool's licence allows you\n    to do with it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The sign-up form asks you to confirm that you are 16 or older.\nminimum_age:\n  value: '16'\n  text: You may register only if you are at least 16 years old (or older if your local law requires a higher age\n    of digital consent).\n"
source_yaml_url: https://artifacts.apis.io/songbrain-ai/eligibility/songbrain-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from songbrain-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Music
- Video
---
