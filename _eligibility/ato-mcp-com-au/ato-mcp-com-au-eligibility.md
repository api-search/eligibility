---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account is for one person or one business
    type: individual
  - text: One account is for one person or one business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose
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
name: Australian Tax MCP
provenance_date: '2026-11-09'
provider_name: Australian Tax MCP
provider_slug: ato-mcp-com-au
slug: ato-mcp-com-au-eligibility
source_date: '2026-11-09'
source_filename: ato-mcp-com-au-eligibility.yml
source_heading: Eligibility
source_page: https://ato-mcp.com.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Australian Tax MCP\naid: ato-mcp-com-au\nurl: https://ato-mcp.com.au/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account is for one person or one business\n- type: business\n  text: One account is for one person or one business\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ato-mcp-com-au/eligibility/ato-mcp-com-au-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Australian Tax MCP's own page on 2026-11-09.
synthetic: false
tags:
- Tax
- Artificial Intelligence
- Australia
- MCP
- Open Data
---
