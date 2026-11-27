---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Backflip makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: you are of legal age to form a binding contract with Backflip, or if you are under 18, you are using the Service under the supervision of a parent or guardian
    type: individual
  - text: ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS
    type: business
  minimum_age:
    text: IF YOU ARE UNDER 18, YOU ARE USING THE SERVICE UNDER THE SUPERVISION OF A PARENT OR GUARDIAN WHO IS AGREEING TO BE BOUND BY THIS AGREEMENT
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
name: Backflip Ai
provenance_date: '2026-11-09'
provider_name: Backflip Ai
provider_slug: backflip-ai
slug: backflip-ai-eligibility
source_date: '2026-11-09'
source_filename: backflip-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.backflip.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Backflip Ai\naid: backflip-ai\nurl: https://www.backflip.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Backflip makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are of legal age to form a binding contract with Backflip, or if you are under 18, you are using the\n    Service under the supervision of a parent or guardian\n- type: business\n  text: ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS\nrestricted_uses: []\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: IF YOU ARE UNDER 18, YOU ARE USING THE SERVICE UNDER THE SUPERVISION OF A PARENT OR GUARDIAN WHO IS AGREEING\n    TO BE BOUND BY THIS AGREEMENT\n"
source_yaml_url: https://artifacts.apis.io/backflip-ai/eligibility/backflip-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Backflip Ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- CAD
- 3D Design
- Automation
- Platform
---
