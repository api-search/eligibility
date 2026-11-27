---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BE
    - NL
    source: https://agent.co-legal.be/legal/terms
    text: Belgian (Vlaams Gewest primary) and Dutch private-client law only.
  entity_types:
  - text: Bent u partner-kantoor met een Co·Legal werkomgeving? Dan bent u de verwerkingsverantwoordelijke en treedt Co-Legal op als verwerker
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No confidential client data in chat
    text: Deel geen vertrouwelijke cliëntgegevens.
  - summary: No confidential case documents in scheduling form
    text: Gebruik het planningsformulier niet om vertrouwelijke dossierstukken te delen.
  - source: https://agent.co-legal.be/legal/terms
    summary: No attorney-client relationship or advice
    text: Using this agent creates NO attorney-client (advocaat-cliënt) relationship.
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
name: Co-Legal
provenance_date: '2026-11-09'
provider_name: Co-Legal
provider_slug: co-legal-be
slug: co-legal-be-eligibility
source_date: '2026-11-09'
source_filename: co-legal-be-eligibility.yml
source_heading: Eligibility
source_page: https://co-legal.be/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Co-Legal\naid: co-legal-be\nurl: https://co-legal.be/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://agent.co-legal.be/legal/terms\n  - https://co-legal.be/legal\ncountries:\n  served:\n  - BE\n  - NL\n  excluded: []\n  text: Belgian (Vlaams Gewest primary) and Dutch private-client law only.\n  source: https://agent.co-legal.be/legal/terms\nentity_types:\n- type: business\n  text: Bent u partner-kantoor met een Co·Legal werkomgeving? Dan bent u de verwerkingsverantwoordelijke en treedt\n    Co-Legal op als verwerker\nrestricted_uses:\n- summary: No confidential client data in chat\n  text: Deel geen\
  \ vertrouwelijke cliëntgegevens.\n- summary: No confidential case documents in scheduling form\n  text: Gebruik het planningsformulier niet om vertrouwelijke dossierstukken te delen.\n- summary: No attorney-client relationship or advice\n  text: Using this agent creates NO attorney-client (advocaat-cliënt) relationship.\n  source: https://agent.co-legal.be/legal/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/co-legal-be/eligibility/co-legal-be-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Co-Legal's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Legal Research
- Tax
- Case Law
- Legislation
- Company Registry
- VAT Validation
- Belgium
- Netherlands
- European Union
- A2A
- MCP
- Agent-Native
- Artificial Intelligence
- Legal Tech
---
