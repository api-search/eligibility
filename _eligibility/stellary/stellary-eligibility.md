---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18, you may only use the Service with the consent of a parent or legal guardian.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Malware, spam, harmful content
    text: Not use the Service to transmit malware, spam, or any harmful content
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
name: Stellary
provenance_date: '2026-11-10'
provider_name: Stellary
provider_slug: stellary
slug: stellary-eligibility
source_date: '2026-11-10'
source_filename: stellary-eligibility.yml
source_heading: Eligibility
source_page: https://stellary.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stellary\naid: stellary\nurl: https://stellary.co/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18, you may only use the Service with the consent of a parent or legal guardian.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Malware, spam, harmful content\n  text: Not use the Service to transmit malware, spam, or any harmful content\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/stellary/eligibility/stellary-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Stellary's own page on 2026-11-10.
synthetic: false
tags:
- Project Management
- Productivity
- AI Agents
- Agent Orchestration
- MCP
- Remote MCP
- Developer Tools
- Software-as-a-Service
- Collaboration
---
