---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Calling any endpoint — by a human or by an autonomous agent acting on a human's behalf — constitutes acceptance of these terms.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions evasion and harassment
    text: Do not use the service to harass, defame, or target individuals; to evade sanctions or launder funds;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: no account, no API key
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cerberus Index
provenance_date: '2026-11-09'
provider_name: Cerberus Index
provider_slug: cerberusindex-com
slug: cerberusindex-com-eligibility
source_date: '2026-11-09'
source_filename: cerberusindex-com-eligibility.yml
source_heading: Eligibility
source_page: https://cerberusindex.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cerberus Index\naid: cerberusindex-com\nurl: https://cerberusindex.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Calling any endpoint — by a human or by an autonomous agent acting on a human's behalf — constitutes acceptance\n    of these terms.\nrestricted_uses:\n- summary: Sanctions evasion and harassment\n  text: Do not use the service to harass, defame, or target individuals; to evade sanctions or launder funds;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: no account, no API key\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cerberusindex-com/eligibility/cerberusindex-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Cerberus Index's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Safety
- XRPL
- Tokens
- Autonomous Agents
---
