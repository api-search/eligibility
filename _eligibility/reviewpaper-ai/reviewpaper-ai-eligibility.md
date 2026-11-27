---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These terms are an agreement between you and Apoorv Saxena, an individual based in India
    type: individual
  - text: If you use reviewpaper.ai for an organization, you confirm you may accept these terms on its behalf.
    type: business
  minimum_age:
    text: You must be at least 16 to use reviewpaper.ai, and if you are under 18 you need a parent or guardian's consent.
    value: '16'
  restricted_uses:
  - summary: Venue confidentiality and LLM rules
    text: If you upload someone else's submission, you must follow your venue's policy on using LLMs and its confidentiality rules.
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
name: reviewpaper-ai
provenance_date: '2026-11-10'
provider_name: reviewpaper-ai
provider_slug: reviewpaper-ai
slug: reviewpaper-ai-eligibility
source_date: '2026-11-10'
source_filename: reviewpaper-ai-eligibility.yml
source_heading: Eligibility
source_page: https://reviewpaper.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: reviewpaper-ai\naid: reviewpaper-ai\nurl: https://reviewpaper.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These terms are an agreement between you and Apoorv Saxena, an individual based in India\n- type: business\n  text: If you use reviewpaper.ai for an organization, you confirm you may accept these terms on its behalf.\nrestricted_uses:\n- summary: Venue confidentiality and LLM rules\n  text: If you upload someone else's submission, you must follow your venue's policy on using LLMs and its confidentiality\n    rules.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 to use reviewpaper.ai, and if you are under 18 you need a parent or guardian's consent.\n"
source_yaml_url: https://artifacts.apis.io/reviewpaper-ai/eligibility/reviewpaper-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from reviewpaper-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Peer Review
- Academic
- Natural Language Processing
- Research Tools
---
