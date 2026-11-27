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
    served: []
    text: You are not located in a country or territory subject to comprehensive sanctions (currently, Crimea, the Republic of Cuba, the Islamic Republic of Iran, the Democratic People's Republic of Korea, and the Syrian Arab Republic).
  minimum_age:
    text: If you are under 13 years old, you may not use the Services.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You authorize us to verify any information through any source including, but not limited to the use of third-party identity verification systems.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Opendorse
provenance_date: '2026-11-10'
provider_name: Opendorse
provider_slug: opendorse
slug: opendorse-eligibility
source_date: '2026-11-10'
source_filename: opendorse-eligibility.yml
source_heading: Eligibility
source_page: https://biz.opendorse.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opendorse\naid: opendorse\nurl: https://biz.opendorse.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You are not located in a country or territory subject to comprehensive sanctions (currently, Crimea, the\n    Republic of Cuba, the Islamic Republic of Iran, the Democratic People's Republic of Korea, and the Syrian Arab\n    Republic).\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You authorize us to verify any information through any source including, but not limited\
  \ to the use of third-party\n    identity verification systems.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years old, you may not use the Services.\n"
source_yaml_url: https://artifacts.apis.io/opendorse/eligibility/opendorse-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from Opendorse's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Athletes
- Name Image Likeness
- NIL
- Marketplace
- Endorsements
- Social Media
- Compliance
- Higher Education
- Payments
- Marketing
---
