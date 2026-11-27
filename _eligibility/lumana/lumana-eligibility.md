---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the legal entity accepting this Agreement and/or executing an Order
    type: business
  - text: on his or her own behalf, then such individual.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: Customer shall not transfer, export, re-export, import, re-import or divert any Company materials
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
name: Lumana
provenance_date: '2026-11-09'
provider_name: Lumana
provider_slug: lumana
slug: lumana-eligibility
source_date: '2026-11-09'
source_filename: lumana-eligibility.yml
source_heading: Eligibility
source_page: https://www.lumana.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lumana\naid: lumana\nurl: https://www.lumana.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the legal entity accepting this Agreement and/or executing an Order\n- type: individual\n  text: on his or her own behalf, then such individual.\nrestricted_uses:\n- summary: Export control compliance\n  text: Customer shall not transfer, export, re-export, import, re-import or divert any Company materials\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lumana/eligibility/lumana-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Lumana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Security
- Artificial Intelligence
- Computer Vision
- Physical Security
- Surveillance
- Video Management
- Access Control
---
