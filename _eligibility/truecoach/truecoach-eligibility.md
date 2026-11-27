---
claim_count: 6
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
    text: any embargoed or terrorist-supporting country or region (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)
  entity_types:
  - text: Such businesses authorize End Users, as defined herein, to use the Services on the businesses behalf
    type: business
  - text: You must be at least 18 years of age to access or use the Services or create an account.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to access or use the Services or create an account.
    value: '18'
  restricted_uses:
  - summary: Minors
    text: The Services are not directed at children. You must be at least 18 years of age to access or use the Services or create an account.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to create an account and specify a password in order to use the Services. To create an account, You must be eligible as specified in section 2, provide contact information, and submit any other form of authentication as determined by Xplor in its sole discretion.
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
name: TrueCoach
provenance_date: '2026-11-10'
provider_name: TrueCoach
provider_slug: truecoach
slug: truecoach-eligibility
source_date: '2026-11-10'
source_filename: truecoach-eligibility.yml
source_heading: Eligibility
source_page: https://xplor.com/truecoach-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueCoach\naid: truecoach\nurl: https://xplor.com/truecoach-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: any embargoed or terrorist-supporting country or region (currently Cuba, Iran, North Korea, Sudan, Syria\n    or Crimea)\nentity_types:\n- type: business\n  text: Such businesses authorize End Users, as defined herein, to use the Services on the businesses behalf\n- type: individual\n  text: You must be at least 18 years of age to access or use the Services or create an account.\nrestricted_uses:\n- summary:\
  \ Minors\n  text: The Services are not directed at children. You must be at least 18 years of age to access or use the Services\n    or create an account.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to create an account and specify a password in order to use the Services. To create\n    an account, You must be eligible as specified in section 2, provide contact information, and submit any other\n    form of authentication as determined by Xplor in its sole discretion.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to access or use the Services or create an account.\n"
source_yaml_url: https://artifacts.apis.io/truecoach/eligibility/truecoach-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from TrueCoach's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fitness
- Personal Training
- Coaching
- Workouts
- Nutrition
- Health
- Software-as-a-Service
---
