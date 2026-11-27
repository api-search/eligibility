---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCESSING AND USING THE SERVICE ON BEHALF OF A COMPANY (SUCH AS YOUR EMPLOYER) OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND THAT COMPANY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Free Service for evaluation only
    text: Customer may access and use the Free Service solely to evaluate the Service to determine if the Service meets Customer’s needs.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: No Order Form is binding on Provider until accepted in writing by Provider.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Anzenna
provenance_date: '2026-11-09'
provider_name: Anzenna
provider_slug: anzenna
slug: anzenna-eligibility
source_date: '2026-11-09'
source_filename: anzenna-eligibility.yml
source_heading: Eligibility
source_page: https://www.anzenna.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anzenna\naid: anzenna\nurl: https://www.anzenna.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCESSING AND USING THE SERVICE ON BEHALF OF A COMPANY (SUCH AS YOUR EMPLOYER) OR OTHER LEGAL\n    ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND THAT COMPANY\nrestricted_uses:\n- summary: Free Service for evaluation only\n  text: Customer may access and use the Free Service solely to evaluate the Service to determine if the Service\n    meets Customer’s needs.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: true\n  text: No Order Form is binding on Provider until accepted in writing by Provider.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anzenna/eligibility/anzenna-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Anzenna's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Insider Risk
- Cybersecurity
- SOC
- Data Loss Prevention
- Shadow AI
- Identity
- AI Agents
---
