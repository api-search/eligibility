---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representations that the Service is appropriate or available for use in other locations.
  minimum_age:
    text: you are of legal age to form a binding contract with Company
    value: null
  restricted_uses:
  - summary: Prohibited uses per agreement
    text: you agree not to use the Service for any purpose that is prohibited by this Agreement or by applicable law.
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
name: Paper
provenance_date: '2026-11-10'
provider_name: Paper
provider_slug: paper
slug: paper-eligibility
source_date: '2026-11-10'
source_filename: paper-eligibility.yml
source_heading: Eligibility
source_page: https://paper.design/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paper\naid: paper\nurl: https://paper.design/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representations that the Service is appropriate or available for use in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses per agreement\n  text: you agree not to use the Service for any purpose that is prohibited by this Agreement or by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract\
  \ with Company\n"
source_yaml_url: https://artifacts.apis.io/paper/eligibility/paper-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Paper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Design
- Design Tools
- MCP
- Agents
- HTML
- CSS
- Developer Tools
- Design to Code
---
