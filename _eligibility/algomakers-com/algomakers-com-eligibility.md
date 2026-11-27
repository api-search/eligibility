---
claim_count: 1
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
  - summary: Regulated activity without authorisation
    text: ou para prestar serviço que exija autorização regulatória que você não possua.
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
name: AlgoMaker
provenance_date: '2026-11-09'
provider_name: AlgoMaker
provider_slug: algomakers-com
slug: algomakers-com-eligibility
source_date: '2026-11-09'
source_filename: algomakers-com-eligibility.yml
source_heading: Eligibility
source_page: https://algomakers.com/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlgoMaker\naid: algomakers-com\nurl: https://algomakers.com/termos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Regulated activity without authorisation\n  text: ou para prestar serviço que exija autorização regulatória que você não possua.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/algomakers-com/eligibility/algomakers-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AlgoMaker's own page on 2026-11-09.
synthetic: false
tags:
- Quantitative Trading
- AI Agents
- MCP
- Finance
- Institutional
---
