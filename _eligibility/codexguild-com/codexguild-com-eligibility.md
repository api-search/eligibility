---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 and give accurate account information.
    type: individual
  - text: If you use CodexGuild for an organisation, you confirm you may bind it to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 and give accurate account information.
    value: '16'
  restricted_uses:
  - summary: Unlawful use or infringement
    text: use the service for anything unlawful or to infringe others’ rights
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
name: CodexGuild
provenance_date: '2026-11-09'
provider_name: CodexGuild
provider_slug: codexguild-com
slug: codexguild-com-eligibility
source_date: '2026-11-09'
source_filename: codexguild-com-eligibility.yml
source_heading: Eligibility
source_page: https://codexguild.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CodexGuild\naid: codexguild-com\nurl: https://codexguild.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 and give accurate account information.\n- type: business\n  text: If you use CodexGuild for an organisation, you confirm you may bind it to these Terms.\nrestricted_uses:\n- summary: Unlawful use or infringement\n  text: use the service for anything unlawful or to infringe others’ rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n\
  \  text: You must be at least 16 and give accurate account information.\n"
source_yaml_url: https://artifacts.apis.io/codexguild-com/eligibility/codexguild-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CodexGuild's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Coding Agents
- Agent Security
- MCP
- Software Supply Chain
- Package Security
- Developer Tools
- Agent Skills
---
