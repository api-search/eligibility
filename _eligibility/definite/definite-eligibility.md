---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Agreement is between Luabase, Inc. and the company or person accessing or using the Product.
    type: individual
  - text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Definite
provenance_date: '2026-11-09'
provider_name: Definite
provider_slug: definite
slug: definite-eligibility
source_date: '2026-11-09'
source_filename: definite-eligibility.yml
source_heading: Eligibility
source_page: https://www.definite.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Definite\naid: definite\nurl: https://www.definite.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Agreement is between Luabase, Inc. and the company or person accessing or using the Product.\n- type: business\n  text: If you are accessing or using the Product on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/definite/eligibility/definite-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Definite's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Analytics
- Business Intelligence
- Data Integration
- Data Warehouse
- Lakehouse
- Semantic Layer
- Artificial Intelligence
- AI Agents
- MCP
- ETL
---
