---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use our Service.
    value: '18'
  restricted_uses:
  - summary: Unauthorized commercial purpose
    text: Use the Service for any unauthorized commercial purpose.
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
name: Imagine Ai
provenance_date: '2026-11-09'
provider_name: Imagine Ai
provider_slug: imagine-ai
slug: imagine-ai-eligibility
source_date: '2026-11-09'
source_filename: imagine-ai-eligibility.yml
source_heading: Eligibility
source_page: https://useimagine.ai/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imagine Ai\naid: imagine-ai\nurl: https://useimagine.ai/user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our Service.\nrestricted_uses:\n- summary: Unauthorized commercial purpose\n  text: Use the Service for any unauthorized commercial purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Service.\n"
source_yaml_url: https://artifacts.apis.io/imagine-ai/eligibility/imagine-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Imagine Ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- B2B
- Content Marketing
- LinkedIn
- Thought Leadership
- Social Media
- Lead Generation
- Personas
- Y Combinator
- Software-as-a-Service
---
