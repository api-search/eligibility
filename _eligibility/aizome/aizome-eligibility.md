---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Site is only intended for individuals aged eighteen (18) years or older.
    type: individual
  minimum_age:
    text: the Site is only intended for individuals aged eighteen (18) years or older.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: use our Site for any illegal, immoral or unauthorized purpose
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
name: Aizome
provenance_date: '2026-11-09'
provider_name: Aizome
provider_slug: aizome
slug: aizome-eligibility
source_date: '2026-11-09'
source_filename: aizome-eligibility.yml
source_heading: Eligibility
source_page: https://www.aizome.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aizome\naid: aizome\nurl: https://www.aizome.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the Site is only intended for individuals aged eighteen (18) years or older.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: use our Site for any illegal, immoral or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Site is only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/aizome/eligibility/aizome-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aizome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- AI Agents
- Identity and Access
- Governance
- Compliance
- Agent Security
- Enterprise AI
---
