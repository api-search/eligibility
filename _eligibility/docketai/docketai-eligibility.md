---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To use the Services, you must be at least 18 years old and have the legal capacity to enter into this Agreement.
    value: '18'
  restricted_uses:
  - summary: Prohibited by law
    text: You may not use the Services if you are prohibited from doing so by law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to create an account to access certain features of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Docket
provenance_date: '2026-11-09'
provider_name: Docket
provider_slug: docketai
slug: docketai-eligibility
source_date: '2026-11-09'
source_filename: docketai-eligibility.yml
source_heading: Eligibility
source_page: https://www.docket.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docket\naid: docketai\nurl: https://www.docket.io/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited by law\n  text: You may not use the Services if you are prohibited from doing so by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to create an account to access certain features of the Services.\nminimum_age:\n  value: '18'\n  text: To use the Services, you must be at least 18 years old and have the legal capacity to enter into this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/docketai/eligibility/docketai-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Docket's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agentic Marketing
- Sales Enablement
- Demand Generation
- Marketing Automation
- Conversational AI
- Lead Qualification
- Go-To-Market
- MCP
---
