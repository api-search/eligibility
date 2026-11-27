---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - IQ
    - LY
    - KP
    - SD
    - SY
    served: []
    text: you agree to the foregoing and represents and warrants that you are not located in, under the control of, or a national or resident of any such country. (Cuba, Iran, Iraq, Libya, North Korea, Sudan, Syria named as restricted destinations)
  minimum_age:
    text: Minors are not eligible to use the Cyscale Resources, and we ask that they do not submit any personal information to us.
    value: not stated
  restricted_uses:
  - summary: Nuclear, chemical or biological weapons
    text: including, without limitation, for the development, design, manufacture or production of nuclear, chemical or biological weapons of mass destruction
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- IQ
- LY
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cyscale
provenance_date: '2026-11-09'
provider_name: Cyscale
provider_slug: cyscale
slug: cyscale-eligibility
source_date: '2026-11-09'
source_filename: cyscale-eligibility.yml
source_heading: Eligibility
source_page: https://cyscale.com/policies/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cyscale\naid: cyscale\nurl: https://cyscale.com/policies/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - IQ\n  - LY\n  - KP\n  - SD\n  - SY\n  text: you agree to the foregoing and represents and warrants that you are not located in, under the control of,\n    or a national or resident of any such country. (Cuba, Iran, Iraq, Libya, North Korea, Sudan, Syria named as\n    restricted destinations)\nentity_types: []\nrestricted_uses:\n- summary: Nuclear, chemical or biological weapons\n  text: including, without limitation, for the development, design, manufacture\
  \ or production of nuclear, chemical\n    or biological weapons of mass destruction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: not stated\n  text: Minors are not eligible to use the Cyscale Resources, and we ask that they do not submit any personal information\n    to us.\n"
source_yaml_url: https://artifacts.apis.io/cyscale/eligibility/cyscale-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cyscale's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Security
- CNAPP
- CSPM
- CIEM
- KSPM
- DSPM
- Cloud Compliance
- Kubernetes Security
- Cybersecurity
---
