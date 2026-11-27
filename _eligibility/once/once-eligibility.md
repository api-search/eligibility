---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IQ
    - LY
    - KP
    - IR
    - SY
    - BY
    - RU
    served: []
    text: No Software may be downloaded from the Website/ Application or otherwise exported or re-exported (i) into (or to a national or resident of) Cuba, Iraq, Libya, North Korea, Iran, Syria, Republic of Belarus, Russian Federation
  entity_types:
  - text: Getonce.com is for the personal use of individual Members only and may not be used in connection with any commercial endeavors.
    type: individual
  - text: Organizations, companies, businesses, and/or other entities may not become Members and are not entitled to use the Service or the Website/ Application for any purpose.
    type: business
  minimum_age:
    text: You represent and warrant that You are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You further guarantee and warrant that You will not use the Website/Application for any commercial purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Where the identification provided is inaccurate or incomplete, suspension of the account will occur until identity verification has been satisfactorily completed.
excluded_countries:
- CU
- IQ
- LY
- KP
- IR
- SY
- BY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Once
provenance_date: '2026-11-10'
provider_name: Once
provider_slug: once
slug: once-eligibility
source_date: '2026-11-10'
source_filename: once-eligibility.yml
source_heading: Eligibility
source_page: https://www.getonce.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Once\naid: once\nurl: https://www.getonce.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IQ\n  - LY\n  - KP\n  - IR\n  - SY\n  - BY\n  - RU\n  text: No Software may be downloaded from the Website/ Application or otherwise exported or re-exported (i) into\n    (or to a national or resident of) Cuba, Iraq, Libya, North Korea, Iran, Syria, Republic of Belarus, Russian\n    Federation\nentity_types:\n- type: individual\n  text: Getonce.com is for the personal use of individual Members only and may not be used in connection with any\n    commercial endeavors.\n\
  - type: business\n  text: Organizations, companies, businesses, and/or other entities may not become Members and are not entitled\n    to use the Service or the Website/ Application for any purpose.\nrestricted_uses:\n- summary: No commercial use\n  text: You further guarantee and warrant that You will not use the Website/Application for any commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Where the identification provided is inaccurate or incomplete, suspension of the account will occur until\n    identity verification has been satisfactorily completed.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that You are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/once/eligibility/once-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Once's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Dating
- Social
- Chat
- Mobile
- Community
---
