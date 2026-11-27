---
api_specs:
- filename: spin-ai-entities-api-openapi.yml
  format: yaml
  label: Spin.AI Entities API
  slug: spin-ai-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spin-ai/openapi/spin-ai-entities-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - MM
    - CU
    - IR
    - LY
    - SD
    - SY
    - KP
    served: []
    text: You will not export, re-export, use, or divert the Services to or on behalf of (a) any country that is subject to U.S., EU or UN economic sanctions ... including but not limited to Burma, Cuba, Iran, Libya, Sudan, Syria and North Korea;
  entity_types:
  - text: (2) YOU, AS AN INDIVIDUAL, IN CASE YOU ARE NOT A LEGAL ENTITY.
    type: individual
  - text: IF YOU ARE ENTERING INTO THESE TERMS ON BEHALF OF (AND FOR USE ON BEHALF OF) A COMPANY, GOVERNMENTAL ENTITY OR OTHER ENTITY
    type: business
  - text: This provision applies only if You are the United States Government or a state or local government entity located in the United States
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Terrorism and weapons
    text: You shall not use the Services in connection with the commission of terrorist acts or the design, development, production, or use of nuclear, biological, or chemical weapons; missiles; or unmanned aerial vehicles.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- MM
- CU
- IR
- LY
- SD
- SY
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Spin.AI
provenance_date: '2026-11-10'
provider_name: Spin.AI
provider_slug: spin-ai
slug: spin-ai-eligibility
source_date: '2026-11-10'
source_filename: spin-ai-eligibility.yml
source_heading: Eligibility
source_page: https://spin.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spin.AI\naid: spin-ai\nurl: https://spin.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - MM\n  - CU\n  - IR\n  - LY\n  - SD\n  - SY\n  - KP\n  text: You will not export, re-export, use, or divert the Services to or on behalf of (a) any country that is subject\n    to U.S., EU or UN economic sanctions ... including but not limited to Burma, Cuba, Iran, Libya, Sudan, Syria\n    and North Korea;\nentity_types:\n- type: individual\n  text: (2) YOU, AS AN INDIVIDUAL, IN CASE YOU ARE NOT A LEGAL ENTITY.\n- type: business\n  text: IF YOU ARE ENTERING INTO THESE TERMS ON BEHALF\
  \ OF (AND FOR USE ON BEHALF OF) A COMPANY, GOVERNMENTAL ENTITY\n    OR OTHER ENTITY\n- type: government\n  text: This provision applies only if You are the United States Government or a state or local government entity\n    located in the United States\nrestricted_uses:\n- summary: Terrorism and weapons\n  text: You shall not use the Services in connection with the commission of terrorist acts or the design, development,\n    production, or use of nuclear, biological, or chemical weapons; missiles; or unmanned aerial vehicles.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spin-ai/eligibility/spin-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Spin.AI's own page on 2026-11-10.
synthetic: false
tags:
- Backup
- Compliance
- Data Protection
- Ransomware
- SaaS Security
---
