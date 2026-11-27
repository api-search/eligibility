---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live, and able to enter a contract.
    type: individual
  - text: If you use Arketo for an organization, you confirm you are allowed to bind that organization to these terms.
    type: business
  minimum_age:
    text: You must be at least 18, or the age of majority where you live
    value: '18'
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
name: Arketo
provenance_date: '2026-11-09'
provider_name: Arketo
provider_slug: arketo-ai
slug: arketo-ai-eligibility
source_date: '2026-11-09'
source_filename: arketo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://arketo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arketo\naid: arketo-ai\nurl: https://arketo.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live, and able to enter a contract.\n- type: business\n  text: If you use Arketo for an organization, you confirm you are allowed to bind that organization to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live\n"
source_yaml_url: https://artifacts.apis.io/arketo-ai/eligibility/arketo-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Arketo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Architecture
- Developer Tools
- LLM
- Software Engineering
---
