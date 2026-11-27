---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IQ
    - LY
    - KP
    - IR
    - SD
    - SY
    served: []
    text: 'No Services or software from the Website may be downloaded or exported: into (or to a national or resident of) Cuba, Iraq, Libya, North Korea, Iran, Sudan, Syria, or any other country to which the United States has embargoed goods'
  entity_types:
  - text: By accessing and/or using the Services, you represent and warrant that you are at least eighteen (18) years of age, and are otherwise legally qualified to enter into and form contracts under applicable law.
    type: individual
  - text: If you are using the Services on behalf of a business entity, you further represent and warrant that you are authorized to act and enter into contracts on behalf of that business entity.
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct
    text: You must not use the Services in any way that causes, or may cause, damage to the Services or impairment of the availability or accessibility of the Services, or in any way which is unlawful, illegal, fraudulent or harmful
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IQ
- LY
- KP
- IR
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Renpho
provenance_date: '2026-11-10'
provider_name: Renpho
provider_slug: renpho
slug: renpho-eligibility
source_date: '2026-11-10'
source_filename: renpho-eligibility.yml
source_heading: Eligibility
source_page: https://renpho.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Renpho\naid: renpho\nurl: https://renpho.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IQ\n  - LY\n  - KP\n  - IR\n  - SD\n  - SY\n  text: 'No Services or software from the Website may be downloaded or exported: into (or to a national or resident\n    of) Cuba, Iraq, Libya, North Korea, Iran, Sudan, Syria, or any other country to which the United States has\n    embargoed goods'\nentity_types:\n- type: individual\n  text: By accessing and/or using the Services, you represent and warrant that you are at least eighteen (18) years\n    of age, and are\
  \ otherwise legally qualified to enter into and form contracts under applicable law.\n- type: business\n  text: If you are using the Services on behalf of a business entity, you further represent and warrant that you\n    are authorized to act and enter into contracts on behalf of that business entity.\nrestricted_uses:\n- summary: Prohibited conduct\n  text: You must not use the Services in any way that causes, or may cause, damage to the Services or impairment\n    of the availability or accessibility of the Services, or in any way which is unlawful, illegal, fraudulent or\n    harmful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/renpho/eligibility/renpho-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Renpho's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wellness
- Health Tech
- IoT
- Consumer Electronics
---
