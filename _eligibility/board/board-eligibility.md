---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Currently, we only ship Products to addresses within the United States and Canada, excluding residents of the province of Quebec.
  entity_types:
  - text: All orders of Products must be for your personal use only.
    type: individual
  minimum_age:
    text: If you are under the age of majority where you reside, you may use the Service only with the express consent of your parent or guardian.
    value: age of majority
  restricted_uses:
  - summary: No resale of Products
    text: you hereby agree not to resell or distribute such Products for any commercial purposes.
  - summary: Export restrictions
    text: not to export or re-export any of the Content to countries or persons prohibited under the export control laws.
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
name: Board
provenance_date: '2026-11-09'
provider_name: Board
provider_slug: board
slug: board-eligibility
source_date: '2026-11-09'
source_filename: board-eligibility.yml
source_heading: Eligibility
source_page: https://board.fun/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Board\naid: board\nurl: https://board.fun/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Currently, we only ship Products to addresses within the United States and Canada, excluding residents of\n    the province of Quebec.\nentity_types:\n- type: individual\n  text: All orders of Products must be for your personal use only.\nrestricted_uses:\n- summary: No resale of Products\n  text: you hereby agree not to resell or distribute such Products for any commercial purposes.\n- summary: Export restrictions\n  text: not to export or re-export any\
  \ of the Content to countries or persons prohibited under the export control\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: If you are under the age of majority where you reside, you may use the Service only with the express consent\n    of your parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/board/eligibility/board-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Board's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Board Games
- Agentic Commerce
- Universal Commerce Protocol
- Shopify
- MCP
---
