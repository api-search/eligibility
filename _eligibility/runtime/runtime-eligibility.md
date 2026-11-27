---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old and provide accurate information to create an account.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Violate any applicable laws or regulations, including sanctions, anti-money laundering, consumer protection, and privacy laws
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
name: Runtime
provenance_date: '2026-11-10'
provider_name: Runtime
provider_slug: runtime
slug: runtime-eligibility
source_date: '2026-11-10'
source_filename: runtime-eligibility.yml
source_heading: Eligibility
source_page: https://www.runtm.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runtime\naid: runtime\nurl: https://www.runtm.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Violate any applicable laws or regulations, including sanctions, anti-money laundering, consumer protection,\n    and privacy laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and provide accurate information to create an account.\n"
source_yaml_url: https://artifacts.apis.io/runtime/eligibility/runtime-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Runtime's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Coding Agents
- Developer Tools
- AI Infrastructure
- Sandbox
- Agent Orchestration
- DevOps
- Cloud
---
