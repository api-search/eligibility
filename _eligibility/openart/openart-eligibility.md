---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in any U.S.-embargoed country
  entity_types:
  - text: You must be at least 18 years old to use OpenArt.
    type: individual
  - text: for your personal or business purposes
    type: business
  minimum_age:
    text: You must be at least 18 years old to use OpenArt.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You may not use or export the Services except as authorized by U.S. and other applicable laws.
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
name: Openart
provenance_date: '2026-11-10'
provider_name: Openart
provider_slug: openart
slug: openart-eligibility
source_date: '2026-11-10'
source_filename: openart-eligibility.yml
source_heading: Eligibility
source_page: https://openart.ai/suite/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Openart\naid: openart\nurl: https://openart.ai/suite/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in any U.S.-embargoed country\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use OpenArt.\n- type: business\n  text: for your personal or business purposes\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You may not use or export the Services except as authorized by U.S. and other applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use OpenArt.\n"
source_yaml_url: https://artifacts.apis.io/openart/eligibility/openart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Openart's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Image Generation
- Video Generation
- Creative Tools
- MCP
---
