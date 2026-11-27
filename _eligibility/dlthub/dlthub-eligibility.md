---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE DLTHUB SERVICE IS NOT DESIGNED TO BE USED BY INDIVIDUAL CONSUMERS AND THE TERMS OF USE APPLY TO ENTERPRISE SUBSCRIBERS.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH DLTHUB
    value: null
  restricted_uses:
  - summary: No use by individual consumers
    text: THE DLTHUB SERVICE IS NOT DESIGNED TO BE USED BY INDIVIDUAL CONSUMERS
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
name: dltHub
provenance_date: '2026-11-09'
provider_name: dltHub
provider_slug: dlthub
slug: dlthub-eligibility
source_date: '2026-11-09'
source_filename: dlthub-eligibility.yml
source_heading: Eligibility
source_page: https://dlthub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dltHub\naid: dlthub\nurl: https://dlthub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THE DLTHUB SERVICE IS NOT DESIGNED TO BE USED BY INDIVIDUAL CONSUMERS AND THE TERMS OF USE APPLY TO ENTERPRISE\n    SUBSCRIBERS.\nrestricted_uses:\n- summary: No use by individual consumers\n  text: THE DLTHUB SERVICE IS NOT DESIGNED TO BE USED BY INDIVIDUAL CONSUMERS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH\
  \ DLTHUB\n"
source_yaml_url: https://artifacts.apis.io/dlthub/eligibility/dlthub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from dltHub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Data Engineering
- ETL
- Data Pipeline
- Python
- Open Source
- Data Integration
- AI Agents
- MCP
---
