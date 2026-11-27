---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Certain Magical features and functionality, including our Core and Advanced offerings, are only available to individuals who have Purchased a paid subscription (“Subscriptions”).
    type: individual
  - text: If you use the Services for business purposes, your use may be subject to certain terms and policies of your business organization
    type: business
  minimum_age:
    text: BY ACCESSING OR USING THE SERVICES, YOU CONFIRM THAT YOU ARE AT LEAST 18 YEARS OLD (OR IF YOU ARE BETWEEN 13 AND 17 YEARS OLD, INCLUSIVE, THAT YOU ARE USING THE SITE, SERVICES AND/OR SOFTWARE ONLY WITH THE APPROVAL OF YOUR PARENT OR GUARDIAN)
    value: '18'
  restricted_uses:
  - summary: Violating law or export controls
    text: (b) Violates any law or regulation, including any applicable export control laws;
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
name: Magical
provenance_date: '2026-11-10'
provider_name: Magical
provider_slug: magical
slug: magical-eligibility
source_date: '2026-11-10'
source_filename: magical-eligibility.yml
source_heading: Eligibility
source_page: https://www.getmagical.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Magical\naid: magical\nurl: https://www.getmagical.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Certain Magical features and functionality, including our Core and Advanced offerings, are only available\n    to individuals who have Purchased a paid subscription (“Subscriptions”).\n- type: business\n  text: If you use the Services for business purposes, your use may be subject to certain terms and policies of\n    your business organization\nrestricted_uses:\n- summary: Violating law or\
  \ export controls\n  text: (b) Violates any law or regulation, including any applicable export control laws;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: BY ACCESSING OR USING THE SERVICES, YOU CONFIRM THAT YOU ARE AT LEAST 18 YEARS OLD (OR IF YOU ARE BETWEEN\n    13 AND 17 YEARS OLD, INCLUSIVE, THAT YOU ARE USING THE SITE, SERVICES AND/OR SOFTWARE ONLY WITH THE APPROVAL\n    OF YOUR PARENT OR GUARDIAN)\n"
source_yaml_url: https://artifacts.apis.io/magical/eligibility/magical-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Magical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Apps
- AI Agents
- Healthcare
- Revenue Cycle Management
- Workflow Automation
- Automation
- Productivity
---
