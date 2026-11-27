---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (or the minimum age required in your jurisdiction) to use the Services.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (or the minimum age required in your jurisdiction) to use the Services.
    value: '13'
  restricted_uses:
  - summary: Prohibited content and illegal activity
    text: Violate any applicable laws, regulations, or third-party rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to verify your age at any time and may suspend or terminate accounts where age requirements are not met.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Apatero
provenance_date: '2026-11-09'
provider_name: Apatero
provider_slug: apatero-ai
slug: apatero-ai-eligibility
source_date: '2026-11-09'
source_filename: apatero-ai-eligibility.yml
source_heading: Eligibility
source_page: https://app.apatero.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apatero\naid: apatero-ai\nurl: https://app.apatero.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (or the minimum age required in your jurisdiction) to use the Services.\nrestricted_uses:\n- summary: Prohibited content and illegal activity\n  text: Violate any applicable laws, regulations, or third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to verify your age at any time and may suspend or terminate accounts where age requirements\n\
  \    are not met.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the minimum age required in your jurisdiction) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/apatero-ai/eligibility/apatero-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Apatero's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Audio Generation
- 3D
- Creator Studio
---
