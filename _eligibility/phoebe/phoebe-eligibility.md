---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This agreement is a legal agreement between you, whether acting as an individual user or on behalf of the company you represent (collectively, "Client")
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
name: Coral
provenance_date: '2026-11-10'
provider_name: Coral
provider_slug: phoebe
slug: phoebe-eligibility
source_date: '2026-11-10'
source_filename: phoebe-eligibility.yml
source_heading: Eligibility
source_page: https://withcoral.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coral\naid: phoebe\nurl: https://withcoral.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This agreement is a legal agreement between you, whether acting as an individual user or on behalf of the\n    company you represent (collectively, \"Client\")\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/phoebe/eligibility/phoebe-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Coral's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- MCP
- SQL
- Data Access
- Data Integration
- Developer Tools
- Open Source
---
