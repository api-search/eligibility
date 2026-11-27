---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The service is aimed at people of full legal age who reside or are established in the European Economic Area
  entity_types:
  - text: The service is aimed at people of full legal age who reside or are established in the European Economic Area and who hold, or are authorised to dispose of, the bank accounts they connect.
    type: individual
  minimum_age:
    text: The service is aimed at people of full legal age
    value: full legal age
  restricted_uses:
  - summary: Only own or authorised accounts
    text: Only connect bank accounts you are authorised to dispose of.
  - summary: Not financial advice
    text: The service is not investment, tax, legal or other financial advice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You create an account by entering your email address and confirming the 6-digit code we send you.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Escher Consulting GmbH
provenance_date: '2026-11-09'
provider_name: Escher Consulting GmbH
provider_slug: banking-mcp-com
slug: banking-mcp-com-eligibility
source_date: '2026-11-09'
source_filename: banking-mcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://banking-mcp.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Escher Consulting GmbH\naid: banking-mcp-com\nurl: https://banking-mcp.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The service is aimed at people of full legal age who reside or are established in the European Economic\n    Area\nentity_types:\n- type: individual\n  text: The service is aimed at people of full legal age who reside or are established in the European Economic\n    Area and who hold, or are authorised to dispose of, the bank accounts they connect.\nrestricted_uses:\n- summary: Only own or authorised accounts\n  text: Only connect bank accounts you are\
  \ authorised to dispose of.\n- summary: Not financial advice\n  text: The service is not investment, tax, legal or other financial advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You create an account by entering your email address and confirming the 6-digit code we send you.\nminimum_age:\n  value: full legal age\n  text: The service is aimed at people of full legal age\n"
source_yaml_url: https://artifacts.apis.io/banking-mcp-com/eligibility/banking-mcp-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Escher Consulting GmbH's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Artificial Intelligence
- Finance
- Open Banking
- MCP
- Europe
---
