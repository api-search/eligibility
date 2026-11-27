---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - BY
    - RU
    served: []
    text: Customer is not, nor is it 50% or more owned by, controlled by, or otherwise acting on behalf of for the benefit of a party or parties subject to Trade Restrictions; (b) a party who is located in, ordinarily resident in, legally organized in or controlled by the government of Cuba, Iran, North Korea, Syria, Belarus, Russia
  entity_types:
  - text: If the user or licensee of the Rescale Platform is an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled and sanctioned end uses
    text: Customer will not use the Rescale Platform in support of any end use or activity prohibited by the U.S. Export Administration Regulations or International Traffic in Arms Regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- BY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rescale
provenance_date: '2026-11-10'
provider_name: Rescale
provider_slug: rescale
slug: rescale-eligibility
source_date: '2026-11-10'
source_filename: rescale-eligibility.yml
source_heading: Eligibility
source_page: https://rescale.com/company/legal/customer-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rescale\naid: rescale\nurl: https://rescale.com/company/legal/customer-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - BY\n  - RU\n  text: Customer is not, nor is it 50% or more owned by, controlled by, or otherwise acting on behalf of for the\n    benefit of a party or parties subject to Trade Restrictions; (b) a party who is located in, ordinarily resident\n    in, legally organized in or controlled by the government of Cuba, Iran, North Korea, Syria, Belarus, Russia\nentity_types:\n- type: government\n  text: If the user or licensee of the Rescale\
  \ Platform is an agency, department, or other entity of the United\n    States Government\nrestricted_uses:\n- summary: Export-controlled and sanctioned end uses\n  text: Customer will not use the Rescale Platform in support of any end use or activity prohibited by the U.S.\n    Export Administration Regulations or International Traffic in Arms Regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rescale/eligibility/rescale-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Rescale's own page on 2026-11-10.
synthetic: false
tags:
- Company
- High Performance Computing
- Simulation
- Cloud
- Engineering
- CAE
- HPC
- AI Physics
- Job
- Compute
---
