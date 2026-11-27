---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    served:
    - US
    - CA
    text: you must (i) be an individual at least 18 years of age or an entity registered in the United States or Canada; embargoed nation including Iran, North Korea
  entity_types:
  - text: be an individual at least 18 years of age
    type: individual
  - text: or an entity registered in the United States or Canada and able to form legally binding contracts under applicable law
    type: business
  minimum_age:
    text: be an individual at least 18 years of age or an entity registered in the United States or Canada
    value: '18'
  restricted_uses:
  - summary: Embargoed nations
    text: (m) access or use the Services from an embargoed nation, including without limitation, Iran, North Korea, or any other country/region that becomes an embargoed nation
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you may be required to complete an identity verification process by sharing certain personal information about yourself
excluded_countries:
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Promise
provenance_date: '2026-11-10'
provider_name: Promise
provider_slug: promise
slug: promise-eligibility
source_date: '2026-11-10'
source_filename: promise-eligibility.yml
source_heading: Eligibility
source_page: https://www.promise-pay.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Promise\naid: promise\nurl: https://www.promise-pay.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded:\n  - IR\n  - KP\n  text: you must (i) be an individual at least 18 years of age or an entity registered in the United States or Canada;\n    embargoed nation including Iran, North Korea\nentity_types:\n- type: individual\n  text: be an individual at least 18 years of age\n- type: business\n  text: or an entity registered in the United States or Canada and able to form legally binding contracts under\n    applicable law\nrestricted_uses:\n- summary: Embargoed nations\n  text:\
  \ (m) access or use the Services from an embargoed nation, including without limitation, Iran, North Korea,\n    or any other country/region that becomes an embargoed nation\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: you may be required to complete an identity verification process by sharing certain personal information\n    about yourself\nminimum_age:\n  value: '18'\n  text: be an individual at least 18 years of age or an entity registered in the United States or Canada\n"
source_yaml_url: https://artifacts.apis.io/promise/eligibility/promise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Promise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Government
- Payments
- GovTech
- Relief
- Utilities
- Fraud Prevention
- Fintech
---
