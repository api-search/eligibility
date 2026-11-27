---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: It is reserved for adults, or minors aged 15 or over with the consent of their legal guardians.
    type: individual
  - text: The service is open to businesses.
    type: business
  minimum_age:
    text: It is reserved for adults, or minors aged 15 or over with the consent of their legal guardians.
    value: '15'
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
name: Imaginode
provenance_date: '2026-11-09'
provider_name: Imaginode
provider_slug: imaginode
slug: imaginode-eligibility
source_date: '2026-11-09'
source_filename: imaginode-eligibility.yml
source_heading: Eligibility
source_page: https://imaginode.ai/en/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imaginode\naid: imaginode\nurl: https://imaginode.ai/en/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: It is reserved for adults, or minors aged 15 or over with the consent of their legal guardians.\n- type: business\n  text: The service is open to businesses.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '15'\n  text: It is reserved for adults, or minors aged 15 or over with the consent of their legal guardians.\n"
source_yaml_url: https://artifacts.apis.io/imaginode/eligibility/imaginode-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Imaginode's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Text-to-Speech
- MCP
- Generative AI
- LLM
- Creative Tools
---
