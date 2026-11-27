---
claim_count: 4
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
    text: a country that is the target of a comprehensive trade embargo by the U.S. government (presently, Cuba, Iran, North Korea, Republic of the Sudan, Syria, or the Crimea region of Ukraine)
  entity_types:
  - text: Your Account is solely for your personal use and may not be shared with anyone else.
    type: individual
  minimum_age:
    text: YOU AFFIRM THAT YOU ARE 18 YEARS OR OLDER, OR, IF YOU ARE NOT THAT AGE, THAT YOU ARE 13 YEARS OR OLDER AND HAVE OBTAINED PARENTAL OR GUARDIAN CONSENT
    value: '13'
  restricted_uses:
  - summary: Personal use only
    text: Your Account is solely for your personal use and may not be shared with anyone else.
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
name: HackerRank
provenance_date: '2026-11-09'
provider_name: HackerRank
provider_slug: hackerrank
slug: hackerrank-eligibility
source_date: '2026-11-09'
source_filename: hackerrank-eligibility.yml
source_heading: Eligibility
source_page: https://www.hackerrank.com/about-us/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HackerRank\naid: hackerrank\nurl: https://www.hackerrank.com/about-us/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: a country that is the target of a comprehensive trade embargo by the U.S. government (presently, Cuba, Iran,\n    North Korea, Republic of the Sudan, Syria, or the Crimea region of Ukraine)\nentity_types:\n- type: individual\n  text: Your Account is solely for your personal use and may not be shared with anyone else.\nrestricted_uses:\n- summary: Personal use only\n  text: Your Account is solely for your personal\
  \ use and may not be shared with anyone else.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: YOU AFFIRM THAT YOU ARE 18 YEARS OR OLDER, OR, IF YOU ARE NOT THAT AGE, THAT YOU ARE 13 YEARS OR OLDER AND\n    HAVE OBTAINED PARENTAL OR GUARDIAN CONSENT\n"
source_yaml_url: https://artifacts.apis.io/hackerrank/eligibility/hackerrank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from HackerRank's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Skills
- Technical Hiring
- Coding Assessment
- Recruiting
- Interviewing
- Education
- Developer Tools
---
