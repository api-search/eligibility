---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY, AND CAPACITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD
    value: '18'
  restricted_uses:
  - summary: No commercial use of the website
    text: solely for your own personal and non-commercial use
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
name: Token
provenance_date: '2026-11-10'
provider_name: Token
provider_slug: token
slug: token-eligibility
source_date: '2026-11-10'
source_filename: token-eligibility.yml
source_heading: Eligibility
source_page: https://www.token.security/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Token\naid: token\nurl: https://www.token.security/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY,\n    AND CAPACITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: No commercial use of the website\n  text: solely for your own personal and non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE\
  \ AT LEAST EIGHTEEN (18) YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/token/eligibility/token-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Token's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Non-Human Identity
- Identity and Access Management
- AI Agents
- MCP
---
