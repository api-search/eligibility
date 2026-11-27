---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you certify that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: access, download, use, or export our Service, or any part thereof, in violation of United States (or other applicable) export laws or regulations.
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
name: Agentio
provenance_date: '2026-11-09'
provider_name: Agentio
provider_slug: agentio
slug: agentio-eligibility
source_date: '2026-11-09'
source_filename: agentio-eligibility.yml
source_heading: Eligibility
source_page: https://www.agentio.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentio\naid: agentio\nurl: https://www.agentio.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: access, download, use, or export our Service, or any part thereof, in violation of United States (or other\n    applicable) export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you certify that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/agentio/eligibility/agentio-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Agentio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AdTech
- Advertising
- Creator Economy
- Influencer Marketing
- Marketing
- Artificial Intelligence
- YouTube
- MCP
- Agents
- Analytics
---
