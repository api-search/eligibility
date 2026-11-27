---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
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
name: Bubble Lab
provenance_date: '2026-11-09'
provider_name: Bubble Lab
provider_slug: bubble-lab
slug: bubble-lab-eligibility
source_date: '2026-11-09'
source_filename: bubble-lab-eligibility.yml
source_heading: Eligibility
source_page: https://bubblelab.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bubble Lab\naid: bubble-lab\nurl: https://bubblelab.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/bubble-lab/eligibility/bubble-lab-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Bubble Lab's own page on 2026-11-09.
synthetic: false
tags:
- Workflow Automation
- AI Agents
- Agentic Workflows
- Integration
- Developer Tools
- TypeScript
- Open Source
- Automation
- SDK
- Low-Code
---
