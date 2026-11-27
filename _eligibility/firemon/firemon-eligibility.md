---
claim_count: 3
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
    text: do not reside in any country on which the United States has embargoed goods, technology and/or services (e.g., Cuba, Iran, North Korea, Sudan, or Syria)
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: commercial use prohibited
    text: You must not access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
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
name: FireMon
provenance_date: '2026-11-09'
provider_name: FireMon
provider_slug: firemon
slug: firemon-eligibility
source_date: '2026-11-09'
source_filename: firemon-eligibility.yml
source_heading: Eligibility
source_page: https://www.firemon.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FireMon\naid: firemon\nurl: https://www.firemon.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: do not reside in any country on which the United States has embargoed goods, technology and/or services\n    (e.g., Cuba, Iran, North Korea, Sudan, or Syria)\nentity_types: []\nrestricted_uses:\n- summary: commercial use prohibited\n  text: You must not access or use for any commercial purposes any part of the Website or any services or materials\n    available through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/firemon/eligibility/firemon-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FireMon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Security
- Firewall
- Policy Management
- Network Security
- Cloud Security
- Compliance
- Microsegmentation
---
