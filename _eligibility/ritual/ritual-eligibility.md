---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    served: []
    text: 'no software from the Services may be downloaded, exported or re-exported: (a) into (or to a national or resident of) Cuba, Crimea, North Korea, Iran, Syria or any other country to which the United States has embargoed goods'
  entity_types:
  - text: you are at least 18 years old or the age of majority in your jurisdiction, and (3) you have the authority to enter into the Agreement.
    type: individual
  minimum_age:
    text: you are at least 18 years old or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Commercial activity restricted
    text: Involves commercial activities and/or sales, such as contests, sweepstakes, or barter; communicating or facilitating any commercial advertisement or solicitation; marketing any goods or services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ritual
provenance_date: '2026-11-10'
provider_name: Ritual
provider_slug: ritual
slug: ritual-eligibility
source_date: '2026-11-10'
source_filename: ritual-eligibility.yml
source_heading: Eligibility
source_page: https://ritual.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ritual\naid: ritual\nurl: https://ritual.com/pages/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  text: 'no software from the Services may be downloaded, exported or re-exported: (a) into (or to a national or\n    resident of) Cuba, Crimea, North Korea, Iran, Syria or any other country to which the United States has embargoed\n    goods'\nentity_types:\n- type: individual\n  text: you are at least 18 years old or the age of majority in your jurisdiction, and (3) you have the authority\n    to enter into the Agreement.\n\
  restricted_uses:\n- summary: Commercial activity restricted\n  text: Involves commercial activities and/or sales, such as contests, sweepstakes, or barter; communicating or\n    facilitating any commercial advertisement or solicitation; marketing any goods or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/ritual/eligibility/ritual-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ritual's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Health
- Wellness
- Supplements
- Nutrition
- E-Commerce
- Subscription
- Direct to Consumer
---
