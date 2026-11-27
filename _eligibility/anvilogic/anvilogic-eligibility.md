---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: AGREE TO THIS AGREEMENT ON BEHALF OF THE ORGANIZATION, COMPANY, OR OTHER LEGAL ENTITY FOR WHICH YOU ACT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export compliance
    text: Customer will comply with all applicable export and import laws, rules, and regulations in connection with Customer’s activities under this Agreement.
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
name: Anvilogic
provenance_date: '2026-11-09'
provider_name: Anvilogic
provider_slug: anvilogic
slug: anvilogic-eligibility
source_date: '2026-11-09'
source_filename: anvilogic-eligibility.yml
source_heading: Eligibility
source_page: https://www.anvilogic.com/legal/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anvilogic\naid: anvilogic\nurl: https://www.anvilogic.com/legal/msa\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: AGREE TO THIS AGREEMENT ON BEHALF OF THE ORGANIZATION, COMPANY, OR OTHER LEGAL ENTITY FOR WHICH YOU ACT\nrestricted_uses:\n- summary: Export compliance\n  text: Customer will comply with all applicable export and import laws, rules, and regulations in connection with\n    Customer’s activities under this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anvilogic/eligibility/anvilogic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Anvilogic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Security Operations
- Detection Engineering
- SIEM
- Threat Detection
- Artificial Intelligence
- Agents
- MCP
- Data Lake
---
