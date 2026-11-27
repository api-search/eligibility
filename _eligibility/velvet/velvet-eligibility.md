---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you can form a legally binding contract with us
    type: individual
  - text: solely for your personal use or internal business purposes, as applicable
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful uses
    text: use the Service in any manner or for any purpose that (i) violates, or promotes the violation of, any Applicable Law
  - summary: Prohibited content in submissions
    text: content that contains nudity or other sexually suggestive content
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
name: Velvet
provenance_date: '2026-11-10'
provider_name: Velvet
provider_slug: velvet
slug: velvet-eligibility
source_date: '2026-11-10'
source_filename: velvet-eligibility.yml
source_heading: Eligibility
source_page: https://velvetlab.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Velvet\naid: velvet\nurl: https://velvetlab.ai/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a legally binding contract with us\n- type: business\n  text: solely for your personal use or internal business purposes, as applicable\nrestricted_uses:\n- summary: Unlawful or harmful uses\n  text: use the Service in any manner or for any purpose that (i) violates, or promotes the violation of, any Applicable\n    Law\n- summary: Prohibited content in submissions\n\
  \  text: content that contains nudity or other sexually suggestive content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/velvet/eligibility/velvet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Velvet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Multimodal AI
- Machine Learning
- Datasets
- Model Evaluation
- Video
- World Models
- Y Combinator
---
