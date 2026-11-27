---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may use the website, hosted check, and skill only if you are 18 or older.
    value: '18'
  restricted_uses:
  - summary: Advisory only, no regulated services
    text: No regulated financial service, security certification, or professional advice is offered.
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
name: hanria-ai
provenance_date: '2026-11-09'
provider_name: hanria-ai
provider_slug: hanria-ai
slug: hanria-ai-eligibility
source_date: '2026-11-09'
source_filename: hanria-ai-eligibility.yml
source_heading: Eligibility
source_page: https://hanria.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hanria-ai\naid: hanria-ai\nurl: https://hanria.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Advisory only, no regulated services\n  text: No regulated financial service, security certification, or professional advice is offered.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the website, hosted check, and skill only if you are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/hanria-ai/eligibility/hanria-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from hanria-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Identity
- Verification
- Payments
- Compliance
- Company
---
