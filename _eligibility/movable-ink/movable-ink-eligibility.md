---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - SD
    - SY
    served: []
    text: you are a Restricted Person if you ... is (1) a national of or an entity existing under the laws of Cuba, Iran, Sudan, Syria, or any other country with which U.S. persons are prohibited from engaging in transactions
  entity_types:
  - text: The Products are not available to individuals under the age of 18.
    type: individual
  - text: If you are using the Products in your capacity as an employee, you must have the ability to bind your employer by your use of the Products.
    type: business
  minimum_age:
    text: the Products are not available to individuals under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Spam and unsolicited email
    text: The Products may not be used for the sending of unsolicited Communications (sometimes called "spam").
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must complete the registration form on the Movable Ink sign-up page in order to use the Products.
excluded_countries:
- CU
- IR
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Movable Ink
provenance_date: '2026-11-10'
provider_name: Movable Ink
provider_slug: movable-ink
slug: movable-ink-eligibility
source_date: '2026-11-10'
source_filename: movable-ink-eligibility.yml
source_heading: Eligibility
source_page: https://movableink.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Movable Ink\naid: movable-ink\nurl: https://movableink.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - SD\n  - SY\n  text: you are a Restricted Person if you ... is (1) a national of or an entity existing under the laws of Cuba,\n    Iran, Sudan, Syria, or any other country with which U.S. persons are prohibited from engaging in transactions\nentity_types:\n- type: individual\n  text: The Products are not available to individuals under the age of 18.\n- type: business\n  text: If you are using the Products in your capacity as an employee, you must\
  \ have the ability to bind your employer\n    by your use of the Products.\nrestricted_uses:\n- summary: Spam and unsolicited email\n  text: The Products may not be used for the sending of unsolicited Communications (sometimes called \"spam\").\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must complete the registration form on the Movable Ink sign-up page in order to use the Products.\nminimum_age:\n  value: '18'\n  text: the Products are not available to individuals under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/movable-ink/eligibility/movable-ink-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Movable Ink's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Personalization
- Email
- Customer Data
- Mobile SDK
- Artificial Intelligence
- AdTech
- Content
- Event
---
