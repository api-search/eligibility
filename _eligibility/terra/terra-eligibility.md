---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - LB
    - IR
    - SY
    - KP
    served: []
    text: (ii) incorporated under the laws of, operating from, or ordinarily resident in a country or territory subject to comprehensive U.S. or Israeli economic or trade sanctions (currently, Cuba, Lebanon, Iran, Syria, North Korea, or the Crimea region of Ukraine)
  entity_types:
  - text: the entity listed on the Order Form signed by the parties
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No testing of unauthorized targets
    text: Customer shall not designate or request testing of any Target for which it does not hold such ownership or authorization.
  - summary: No building competitive product
    text: (viii) access and/or use any Services and/or the Terra IP in order to build a competitive product or service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- LB
- IR
- SY
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Terra
provenance_date: '2026-11-10'
provider_name: Terra
provider_slug: terra
slug: terra-eligibility
source_date: '2026-11-10'
source_filename: terra-eligibility.yml
source_heading: Eligibility
source_page: https://www.terra.security/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Terra\naid: terra\nurl: https://www.terra.security/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - LB\n  - IR\n  - SY\n  - KP\n  text: (ii) incorporated under the laws of, operating from, or ordinarily resident in a country or territory subject\n    to comprehensive U.S. or Israeli economic or trade sanctions (currently, Cuba, Lebanon, Iran, Syria, North Korea,\n    or the Crimea region of Ukraine)\nentity_types:\n- type: business\n  text: the entity listed on the Order Form signed by the parties\nrestricted_uses:\n- summary: No testing of unauthorized targets\n  text: Customer\
  \ shall not designate or request testing of any Target for which it does not hold such ownership\n    or authorization.\n- summary: No building competitive product\n  text: (viii) access and/or use any Services and/or the Terra IP in order to build a competitive product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/terra/eligibility/terra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Terra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Penetration Testing
- Offensive Security
- Red Teaming
- Artificial Intelligence
- AI Agents
---
