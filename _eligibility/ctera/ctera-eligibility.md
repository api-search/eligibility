---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: 'it is not, and it will not permit access to the Software by any user who is: (i) located in, under the control of, or a national or resident of Cuba, Iran, North Korea, Syria, Russia, Belarus'
  entity_types:
  - text: the legal entity identified in the applicable order, order form, statement of work, or other document referencing this Agreement
    type: business
  - text: If Customer is an agency, department, or other entity of the United States Government, or is using the Software on behalf of such an entity
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for inherently dangerous applications
    text: THE SOFTWARE AND HARDWARE ARE NOT INTENDED FOR USE IN CONNECTION WITH ANY INHERENTLY DANGEROUS APPLICATIONS.
  - summary: No service bureau use of antivirus engine
    text: Customer shall not use the Antivirus Engine separately from the CTERA Cyber Protection, in the operation of a service bureau, or for the benefit of any other person or entity
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
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CTERA
provenance_date: '2026-11-09'
provider_name: CTERA
provider_slug: ctera
slug: ctera-eligibility
source_date: '2026-11-09'
source_filename: ctera-eligibility.yml
source_heading: Eligibility
source_page: https://www.ctera.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CTERA\naid: ctera\nurl: https://www.ctera.com/eula/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: 'it is not, and it will not permit access to the Software by any user who is: (i) located in, under the\n    control of, or a national or resident of Cuba, Iran, North Korea, Syria, Russia, Belarus'\nentity_types:\n- type: business\n  text: the legal entity identified in the applicable order, order form, statement of work, or other document referencing\n    this Agreement\n- type: government\n  text: If Customer is an\
  \ agency, department, or other entity of the United States Government, or is using the Software\n    on behalf of such an entity\nrestricted_uses:\n- summary: Not for inherently dangerous applications\n  text: THE SOFTWARE AND HARDWARE ARE NOT INTENDED FOR USE IN CONNECTION WITH ANY INHERENTLY DANGEROUS APPLICATIONS.\n- summary: No service bureau use of antivirus engine\n  text: Customer shall not use the Antivirus Engine separately from the CTERA Cyber Protection, in the operation\n    of a service bureau, or for the benefit of any other person or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ctera/eligibility/ctera-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from CTERA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Storage
- File Storage
- Global File System
- Data Management
- Edge Computing
- Cyber Protection
- Hybrid Cloud
- Unstructured Data
---
