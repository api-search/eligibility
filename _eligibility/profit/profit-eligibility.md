---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - JP
    - CN
    - US
    - CA
    - NZ
    - RU
    - PL
    - GB
    - AL
    - IL
    - IR
    - AR
    served: []
    text: Open to all, except for residents of Japan, China, the United States, Canada, New Zealand, Russia, Poland, the UK, Albania, Israel, Iran, and Argentina.
  entity_types:
  - text: a Non-Professional Subscriber is defined as an individual who subscribes to the service for personal, non-commercial use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial or professional use by non-professional subscribers
    text: Non-Professional Subscribers are prohibited from using the service for any commercial, professional or business purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- JP
- CN
- US
- CA
- NZ
- RU
- PL
- GB
- AL
- IL
- IR
- AR
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Profit.com
provenance_date: '2026-11-10'
provider_name: Profit.com
provider_slug: profit
slug: profit-eligibility
source_date: '2026-11-10'
source_filename: profit-eligibility.yml
source_heading: Eligibility
source_page: https://profit.com/resources/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Profit.com\naid: profit\nurl: https://profit.com/resources/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - JP\n  - CN\n  - US\n  - CA\n  - NZ\n  - RU\n  - PL\n  - GB\n  - AL\n  - IL\n  - IR\n  - AR\n  text: Open to all, except for residents of Japan, China, the United States, Canada, New Zealand, Russia, Poland,\n    the UK, Albania, Israel, Iran, and Argentina.\nentity_types:\n- type: individual\n  text: a Non-Professional Subscriber is defined as an individual who subscribes to the service for personal, non-commercial\n    use only.\nrestricted_uses:\n- summary: No commercial\
  \ or professional use by non-professional subscribers\n  text: Non-Professional Subscribers are prohibited from using the service for any commercial, professional or business\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/profit/eligibility/profit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Profit.com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Analytics
- Software-as-a-Service
---
