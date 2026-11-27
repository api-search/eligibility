---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use Blipsmith.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use Blipsmith.
    value: '18'
  restricted_uses:
  - summary: Illegal use and voice imitation
    text: Don't use Blipsmith to break the law, infringe others' rights, or imitate real people's voices.
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
name: Blipsmith
provenance_date: '2026-11-09'
provider_name: Blipsmith
provider_slug: blipsmith-ai
slug: blipsmith-ai-eligibility
source_date: '2026-11-09'
source_filename: blipsmith-ai-eligibility.yml
source_heading: Eligibility
source_page: https://blipsmith.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blipsmith\naid: blipsmith-ai\nurl: https://blipsmith.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use Blipsmith.\nrestricted_uses:\n- summary: Illegal use and voice imitation\n  text: Don't use Blipsmith to break the law, infringe others' rights, or imitate real people's voices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Blipsmith.\n"
source_yaml_url: https://artifacts.apis.io/blipsmith-ai/eligibility/blipsmith-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Blipsmith's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Sound
- Gaming
- Generator
- Software-as-a-Service
---
