---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is intended for business and professional use.
    type: business
  minimum_age:
    text: To use the Website or book a demo, you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Confidential or regulated information in demo requests
    text: do not send us confidential, privileged, or regulated information (such as non-public financial or deal information), sensitive personal information, or personal information about other people
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
name: Cerenovus
provenance_date: '2026-11-09'
provider_name: Cerenovus
provider_slug: cerenovus
slug: cerenovus-eligibility
source_date: '2026-11-09'
source_filename: cerenovus-eligibility.yml
source_heading: Eligibility
source_page: https://snowstone.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cerenovus\naid: cerenovus\nurl: https://snowstone.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Website is intended for business and professional use.\nrestricted_uses:\n- summary: Confidential or regulated information in demo requests\n  text: do not send us confidential, privileged, or regulated information (such as non-public financial or deal\n    information), sensitive personal information, or personal information about other people\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: To use the Website or book a demo, you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/cerenovus/eligibility/cerenovus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cerenovus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Enterprise Software
- Decision Intelligence
- Knowledge Management
- Private Equity
- Due Diligence
- MCP
- Y Combinator
---
