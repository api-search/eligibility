---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to create an account or use the Services.
    type: individual
  - text: If you use the Services on behalf of a company, team, school, or other organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old to create an account or use the Services.
    value: '13'
  restricted_uses:
  - summary: Automated decisions with significant effects
    text: make automated decisions with legal or similarly significant effects on a person unless you have appropriate human review and legal authority
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
name: Aside
provenance_date: '2026-11-09'
provider_name: Aside
provider_slug: aside
slug: aside-eligibility
source_date: '2026-11-09'
source_filename: aside-eligibility.yml
source_heading: Eligibility
source_page: https://aside.com/policy/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aside\naid: aside\nurl: https://aside.com/policy/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to create an account or use the Services.\n- type: business\n  text: If you use the Services on behalf of a company, team, school, or other organization, you represent that\n    you have authority to bind that organization to these Terms.\nrestricted_uses:\n- summary: Automated decisions with significant effects\n  text: make automated decisions with legal or similarly significant effects on a person\
  \ unless you have appropriate\n    human review and legal authority\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to create an account or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/aside/eligibility/aside-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aside's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Browser
- Browser Agent
- Automation
- MCP
- CLI
- Password Manager
- AI Agents
- Browser Automation
- Developer Tools
- Y Combinator
---
