---
claim_count: 6
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
    text: You are not permitted to access or use any of the Services if you are in, under the control of, or a resident of Cuba, Iran, North Korea, Sudan, or Syria
  entity_types:
  - text: For you as an individual user, the Services are only available to an individual whose age is above the minimum age requirement (if any) in the relevant jurisdiction.
    type: individual
  - text: If you are accepting these Terms on behalf of an entity, you represent and warrant that you have full authority to bind the entity to these Terms.
    type: business
  minimum_age:
    text: the Services are only available to an individual whose age is above the minimum age requirement (if any) in the relevant jurisdiction
    value: null
  restricted_uses:
  - summary: Sanctions and embargoed jurisdictions
    text: You are not permitted to access or use any of the Services if you are in, under the control of, or a resident of Cuba, Iran, North Korea, Sudan, or Syria
  - summary: Prohibited weapons development
    text: the development, design, manufacture or production of missiles, nuclear, chemical or biological weapons
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
name: BlockSec
provenance_date: '2026-11-09'
provider_name: BlockSec
provider_slug: blocksec
slug: blocksec-eligibility
source_date: '2026-11-09'
source_filename: blocksec-eligibility.yml
source_heading: Eligibility
source_page: https://blocksec.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlockSec\naid: blocksec\nurl: https://blocksec.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You are not permitted to access or use any of the Services if you are in, under the control of, or a resident\n    of Cuba, Iran, North Korea, Sudan, or Syria\nentity_types:\n- type: individual\n  text: For you as an individual user, the Services are only available to an individual whose age is above the minimum\n    age requirement (if any) in the relevant jurisdiction.\n- type: business\n  text: If you are accepting these Terms\
  \ on behalf of an entity, you represent and warrant that you have full authority\n    to bind the entity to these Terms.\nrestricted_uses:\n- summary: Sanctions and embargoed jurisdictions\n  text: You are not permitted to access or use any of the Services if you are in, under the control of, or a resident\n    of Cuba, Iran, North Korea, Sudan, or Syria\n- summary: Prohibited weapons development\n  text: the development, design, manufacture or production of missiles, nuclear, chemical or biological weapons\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: the Services are only available to an individual whose age is above the minimum age requirement (if any)\n    in the relevant jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/blocksec/eligibility/blocksec-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from BlockSec's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Blockchain
- Web3
- Compliance
- Auditing
---
