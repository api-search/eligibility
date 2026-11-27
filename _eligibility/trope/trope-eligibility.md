---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not promise that the Services will be ... available in every region or environment.
  entity_types:
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization to these terms.
    type: business
  minimum_age:
    text: You must be legally able to enter into a binding agreement to use the Services.
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
name: Trope
provenance_date: '2026-11-10'
provider_name: Trope
provider_slug: trope
slug: trope-eligibility
source_date: '2026-11-10'
source_filename: trope-eligibility.yml
source_heading: Eligibility
source_page: https://trope.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trope\naid: trope\nurl: https://trope.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not promise that the Services will be ... available in every region or environment.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be legally able to enter into a binding agreement to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/trope/eligibility/trope-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Trope's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- ERP
- Enterprise Software
- Computer Use
- MCP
- Automation
---
