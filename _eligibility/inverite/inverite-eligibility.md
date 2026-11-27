---
claim_count: 3
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
    served: []
    text: into, or to a national or resident of, Cuba, Iraq, Libya, Yugoslavia, North Korea, Iran, Syria or any other country to which the U.S. has embargoed goods
  entity_types:
  - text: use the Licensed Materials only for your personal, non-commercial purposes.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only accounts owned by the user
    text: You agree to only use the Inverite Application and Licensed Materials on or in respect of bank or other accounts that you are the sole owner of and have permission to access
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
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Inverite Verification
provenance_date: '2026-11-09'
provider_name: Inverite Verification
provider_slug: inverite
slug: inverite-eligibility
source_date: '2026-11-09'
source_filename: inverite-eligibility.yml
source_heading: Eligibility
source_page: https://inveriteinsights.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inverite Verification\naid: inverite\nurl: https://inveriteinsights.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IQ\n  - LY\n  - KP\n  - IR\n  - SY\n  text: into, or to a national or resident of, Cuba, Iraq, Libya, Yugoslavia, North Korea, Iran, Syria or any other\n    country to which the U.S. has embargoed goods\nentity_types:\n- type: individual\n  text: use the Licensed Materials only for your personal, non-commercial purposes.\nrestricted_uses:\n- summary: Only accounts owned by the user\n  text: You agree to only use the Inverite Application and\
  \ Licensed Materials on or in respect of bank or other\n    accounts that you are the sole owner of and have permission to access\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inverite/eligibility/inverite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Inverite Verification's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Verification
- Risk Scoring
---
