---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The customer decides which one source systems are linked and remain the owner of the synchronized business data.
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
name: DigiData
provenance_date: '2026-11-09'
provider_name: DigiData
provider_slug: digi-data-nl
slug: digi-data-nl-eligibility
source_date: '2026-11-09'
source_filename: digi-data-nl-eligibility.yml
source_heading: Eligibility
source_page: https://www.digi-data.nl/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DigiData\naid: digi-data-nl\nurl: https://www.digi-data.nl/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The customer decides which one source systems are linked and remain the owner of the synchronized business\n    data.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/digi-data-nl/eligibility/digi-data-nl-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from DigiData's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Business Intelligence
- Dashboards
- AI Agents
- MCP
- OData
- Power BI
- Data Integration
- Accounting
- Netherlands
---
