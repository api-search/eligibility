---
api_specs:
- filename: brainmemory-ai-openapi.yaml
  format: yaml
  label: Brain Memory API
  slug: brain-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainmemory-ai/openapi/brainmemory-ai-openapi.yaml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (or the minimum age of digital consent in your jurisdiction) and legally able to enter into these Terms.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (or the minimum age of digital consent in your jurisdiction)
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Brain Cloud and the connector require signing in with a Google account via Firebase authentication.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brain Memory
provenance_date: '2026-11-09'
provider_name: Brain Memory
provider_slug: brainmemory-ai
slug: brainmemory-ai-eligibility
source_date: '2026-11-09'
source_filename: brainmemory-ai-eligibility.yml
source_heading: Eligibility
source_page: https://brainmemory.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brain Memory\naid: brainmemory-ai\nurl: https://brainmemory.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (or the minimum age of digital consent in your jurisdiction) and legally\n    able to enter into these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Brain Cloud and the connector require signing in with a Google account via Firebase authentication.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the\
  \ minimum age of digital consent in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/brainmemory-ai/eligibility/brainmemory-ai-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Brain Memory's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Agents
- Open Source
- Neuroscience
---
