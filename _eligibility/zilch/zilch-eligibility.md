---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: 'You can open an Account with us: resident in the UK (excluding the Isle of Man and the Channel Islands)'
  entity_types:
  - text: 18 years of age or older and have full legal capacity to enter into a contract
    type: individual
  minimum_age:
    text: 18 years of age or older and have full legal capacity to enter into a contract
    value: '18'
  restricted_uses:
  - summary: Gambling and lottery merchants prohibited
    text: it is a Prohibited transaction such as Gambling sites/Lottery sites.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Before we accept your application, we will carry out relevant identification verification checks and if those checks are not satisfactory we may decline your Application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zilch
provenance_date: '2026-11-10'
provider_name: Zilch
provider_slug: zilch
slug: zilch-eligibility
source_date: '2026-11-10'
source_filename: zilch-eligibility.yml
source_heading: Eligibility
source_page: https://www.zilch.com/uk/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zilch\naid: zilch\nurl: https://www.zilch.com/uk/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: 'You can open an Account with us: resident in the UK (excluding the Isle of Man and the Channel Islands)'\nentity_types:\n- type: individual\n  text: 18 years of age or older and have full legal capacity to enter into a contract\nrestricted_uses:\n- summary: Gambling and lottery merchants prohibited\n  text: it is a Prohibited transaction such as Gambling sites/Lottery sites.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Before we\
  \ accept your application, we will carry out relevant identification verification checks and if\n    those checks are not satisfactory we may decline your Application.\nminimum_age:\n  value: '18'\n  text: 18 years of age or older and have full legal capacity to enter into a contract\n"
source_yaml_url: https://artifacts.apis.io/zilch/eligibility/zilch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Zilch's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Buy Now Pay Later
- Consumer Credit
- Digital Wallet
- Cards
- Mastercard
- Fintech
---
