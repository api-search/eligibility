---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business users and is not directed to consumers or to children under the age of 16.
    type: business
  minimum_age:
    text: are at least 18 years old
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
name: Cignara
provenance_date: '2026-11-09'
provider_name: Cignara
provider_slug: cignara
slug: cignara-eligibility
source_date: '2026-11-09'
source_filename: cignara-eligibility.yml
source_heading: Eligibility
source_page: https://cignara.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cignara\naid: cignara\nurl: https://cignara.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for business users and is not directed to consumers or to children under the age\n    of 16.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/cignara/eligibility/cignara-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Cignara's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Conversational AI
- Customer Service
- Voice Agents
- Chat Agents
- Contact Center
- Enterprise AI
- AI Agents
---
