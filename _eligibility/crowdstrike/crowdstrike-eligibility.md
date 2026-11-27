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
    text: you represent and warrant that you are not located in, and shall not use the Website from, any country that is subject to U.S. export restrictions (currently including, but not necessarily limited to, Cuba, Iran, North Korea, Sudan and Syria.
  entity_types:
  - text: This Website is offered and available only to users 18 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available only to users 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful or offensive content
    text: That violates any applicable federal, state, local or international law or regulation
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
name: CrowdStrike
provenance_date: '2026-11-09'
provider_name: CrowdStrike
provider_slug: crowdstrike
slug: crowdstrike-eligibility
source_date: '2026-11-09'
source_filename: crowdstrike-eligibility.yml
source_heading: Eligibility
source_page: https://www.crowdstrike.com/en-us/legal/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CrowdStrike\naid: crowdstrike\nurl: https://www.crowdstrike.com/en-us/legal/website-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: you represent and warrant that you are not located in, and shall not use the Website from, any country that\n    is subject to U.S. export restrictions (currently including, but not necessarily limited to, Cuba, Iran, North\n    Korea, Sudan and Syria.\nentity_types:\n- type: individual\n  text: This Website is offered and available only to users 18 years of age or older.\nrestricted_uses:\n- summary:\
  \ Unlawful or offensive content\n  text: That violates any applicable federal, state, local or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available only to users 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/crowdstrike/eligibility/crowdstrike-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CrowdStrike's own page on 2026-11-09.
synthetic: false
tags:
- Cybersecurity
- Endpoint Security
- Endpoint Detection and Response
- Threat Intelligence
- Cloud Security
- Identity Protection
- Vulnerability Management
- SIEM
- Security Operations
- MCP
---
