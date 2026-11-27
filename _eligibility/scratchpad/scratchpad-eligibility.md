---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ACCESS OR USE THE SERVICE ON BEHALF OF AN ENTITY, YOU HEREBY REPRESENT AND WARRANT TO SCRATCHPAD THAT YOU HAVE THE ACTUAL AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No protected health information
    text: Customer will not submit any patient, medical, or other protected health information or any other special or sensitive categories of data as set forth under any applicable data protection laws.
  - summary: No U.S. Government contracting
    text: Customer represents and warrants that Customer is not entering into this Agreement behalf of the U.S. Government or any agency thereof
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
name: Scratchpad
provenance_date: '2026-11-10'
provider_name: Scratchpad
provider_slug: scratchpad
slug: scratchpad-eligibility
source_date: '2026-11-10'
source_filename: scratchpad-eligibility.yml
source_heading: Eligibility
source_page: https://www.scratchpad.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scratchpad\naid: scratchpad\nurl: https://www.scratchpad.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ACCESS OR USE THE SERVICE ON BEHALF OF AN ENTITY, YOU HEREBY REPRESENT AND WARRANT TO SCRATCHPAD\n    THAT YOU HAVE THE ACTUAL AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT.\nrestricted_uses:\n- summary: No protected health information\n  text: Customer will not submit any patient, medical, or other protected health information or any other special\n    or sensitive categories of data as set forth\
  \ under any applicable data protection laws.\n- summary: No U.S. Government contracting\n  text: Customer represents and warrants that Customer is not entering into this Agreement behalf of the U.S. Government\n    or any agency thereof\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scratchpad/eligibility/scratchpad-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Scratchpad's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Productivity
- Sales
- CRM
- Salesforce
- Revenue Operations
- Artificial Intelligence
- Software-as-a-Service
- MCP
- Agents
- Sales Intelligence
---
