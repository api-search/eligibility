---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan and Syria)
  entity_types:
  - text: CUSTOMER (EITHER AN INDIVIDUAL OR THE ENTITY ON WHOSE BEHALF THIS AGREEMENT IS BEING EXECUTED FOR)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive information
    text: Customer agrees not to use the Tellius subscription service to collect, manage or process sensitive information.
  - summary: Export and sanctions
    text: Customer will not import, export, re-export, transfer or otherwise use the Software or Services in violation of these laws and regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tellius
provenance_date: '2026-11-10'
provider_name: Tellius
provider_slug: tellius
slug: tellius-eligibility
source_date: '2026-11-10'
source_filename: tellius-eligibility.yml
source_heading: Eligibility
source_page: https://www.tellius.com/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tellius\naid: tellius\nurl: https://www.tellius.com/eula\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan and Syria)\nentity_types:\n- type: individual\n  text: CUSTOMER (EITHER AN INDIVIDUAL OR THE ENTITY ON WHOSE BEHALF THIS AGREEMENT IS BEING EXECUTED FOR)\nrestricted_uses:\n- summary: Sensitive information\n  text: Customer agrees not to use the Tellius subscription service to collect, manage or process sensitive information.\n- summary: Export and sanctions\n  text: Customer\
  \ will not import, export, re-export, transfer or otherwise use the Software or Services in violation\n    of these laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tellius/eligibility/tellius-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Tellius's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Business Intelligence
- Agentic Analytics
- Decision Intelligence
- Artificial Intelligence
- Machine Learning
- Data
- Embedded Analytics
- MCP
- Natural Language Query
- Pharmaceuticals
- Consumer Packaged Goods
- Financial Planning
- Real-Time
---
