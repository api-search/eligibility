---
claim_count: 5
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
    text: 'you are not: (i) a citizen or permanent resident of any country on which the United States has embargoed goods, technology and/or services (e.g., Cuba, Iran, North Korea, Sudan, Syria, or Crimea)'
  entity_types:
  - text: “you” or “your” refer to you personally (i.e., the individual who reads and agrees to be bound by these Terms)
    type: individual
  - text: if you access this Site on behalf of a corporation or other legal entity, you and such corporation or other legal entity on whose behalf you access the Site
    type: business
  minimum_age:
    text: The Site is only intended for individuals aged thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: your use of Heeler products and services is in compliance with the applicable U.S. export control and economic sanctions laws and regulations.
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
name: Heeler
provenance_date: '2026-11-09'
provider_name: Heeler
provider_slug: heeler
slug: heeler-eligibility
source_date: '2026-11-09'
source_filename: heeler-eligibility.yml
source_heading: Eligibility
source_page: https://www.heeler.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Heeler\naid: heeler\nurl: https://www.heeler.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: 'you are not: (i) a citizen or permanent resident of any country on which the United States has embargoed\n    goods, technology and/or services (e.g., Cuba, Iran, North Korea, Sudan, Syria, or Crimea)'\nentity_types:\n- type: individual\n  text: “you” or “your” refer to you personally (i.e., the individual who reads and agrees to be bound by these\n    Terms)\n- type: business\n  text: if you access this Site on behalf of a corporation\
  \ or other legal entity, you and such corporation or other\n    legal entity on whose behalf you access the Site\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: your use of Heeler products and services is in compliance with the applicable U.S. export control and economic\n    sanctions laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/heeler/eligibility/heeler-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Heeler's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Application Security
- DevSecOps
- Artificial Intelligence
- Agents
- MCP
- Agent Skills
- Code Security
- Vulnerability Management
- SAST
- Software Composition Analysis
- Secrets Detection
- AI SDLC
---
