---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company or entity identified in the Initial Order Form (“ Customer ”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and weapons-related uses
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical or biological weapons proliferation
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
name: Luminai
provenance_date: '2026-11-10'
provider_name: Luminai
provider_slug: luminai
slug: luminai-eligibility
source_date: '2026-11-10'
source_filename: luminai-eligibility.yml
source_heading: Eligibility
source_page: https://www.luminai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luminai\naid: luminai\nurl: https://www.luminai.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company or entity identified in the Initial Order Form (“ Customer ”)\nrestricted_uses:\n- summary: Export and weapons-related uses\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical or\n    biological weapons proliferation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/luminai/eligibility/luminai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Luminai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health System Operations
- Automation
- Artificial Intelligence
- AI Agents
- Workflow Automation
- Revenue Cycle Management
- Business Process Automation
---
