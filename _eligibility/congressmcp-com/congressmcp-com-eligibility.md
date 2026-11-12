---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment of officials or staff
    text: Use the service to harass individuals, including elected officials or their staff, in a manner that violates applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CongressMCP
provenance_date: '2026-11-09'
provider_name: CongressMCP
provider_slug: congressmcp-com
slug: congressmcp-com-eligibility
source_date: '2026-11-09'
source_filename: congressmcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://congressmcp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CongressMCP\naid: congressmcp-com\nurl: https://congressmcp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment of officials or staff\n  text: Use the service to harass individuals, including elected officials or their staff, in a manner that violates\n    applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email to create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/congressmcp-com/eligibility/congressmcp-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CongressMCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legislation
- Government
- Congress
- State Legislatures
- Bill Tracking
- Model Context Protocol
- AI
- Policy Research
---
