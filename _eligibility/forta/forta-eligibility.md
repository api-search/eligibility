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
    - RU
    served: []
    text: you represent and warrant ... that you are not a citizen of, are not located in ... CRIMEA REGION, CUBA, IRAN, NORTH KOREA, SYRIA, RUSSIA, OR ANY OTHER COUNTRY
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Market manipulation
    text: Using the Services for market manipulation (such as pump and dump schemes, wash trading, self-trading, front running, quote stuffing, and spoofing or layering, regardless of whether prohibited by law), fraud, or other deceptive, misleading, or manipulative activity
  - summary: Financial activities requiring licensing
    text: Using the Services to carry out any financial activities subject to registration or licensing
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
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Forta
provenance_date: '2026-11-09'
provider_name: Forta
provider_slug: forta
slug: forta-eligibility
source_date: '2026-11-09'
source_filename: forta-eligibility.yml
source_heading: Eligibility
source_page: https://www.forta.org/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forta\naid: forta\nurl: https://www.forta.org/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  text: you represent and warrant ... that you are not a citizen of, are not located in ... CRIMEA REGION, CUBA,\n    IRAN, NORTH KOREA, SYRIA, RUSSIA, OR ANY OTHER COUNTRY\nentity_types: []\nrestricted_uses:\n- summary: Market manipulation\n  text: Using the Services for market manipulation (such as pump and dump schemes, wash trading, self-trading, front\n    running, quote stuffing, and spoofing or layering, regardless of whether\
  \ prohibited by law), fraud, or other\n    deceptive, misleading, or manipulative activity\n- summary: Financial activities requiring licensing\n  text: Using the Services to carry out any financial activities subject to registration or licensing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/forta/eligibility/forta-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Forta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Blockchain
- Web3
- Monitoring
- Threat Detection
- DeFi
- GraphQL
- Alerts
- Smart Contracts
---
