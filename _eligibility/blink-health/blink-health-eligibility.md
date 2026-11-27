---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Blink’s Site and Services are only available within the United States, and are not intended for, or directed to, residents of the European Union or European Economic Area or any other persons located outside the United States.
  entity_types:
  - text: you affirm that (i) you are at least eighteen (18) years of age, or (ii) you are accessing the Site and using the Services with the consent and involvement of a parent or guardian.
    type: individual
  - text: you agree to provide Blink accurate and complete information about you and your business
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Personal use of BlinkRx prescriptions
    text: You agree that any prescriptions that you purchase through BlinkRx will be solely for your personal use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Blink may contact you to verify your Account information or request further information from you, and you agree to provide such further information to ensure that you have not fraudulently created your Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blink Health
provenance_date: '2026-11-09'
provider_name: Blink Health
provider_slug: blink-health
slug: blink-health-eligibility
source_date: '2026-11-09'
source_filename: blink-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.blinkhealth.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blink Health\naid: blink-health\nurl: https://www.blinkhealth.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Blink’s Site and Services are only available within the United States, and are not intended for, or directed\n    to, residents of the European Union or European Economic Area or any other persons located outside the United\n    States.\nentity_types:\n- type: individual\n  text: you affirm that (i) you are at least eighteen (18) years of age, or (ii) you are accessing the Site and\n    using the Services with the consent and\
  \ involvement of a parent or guardian.\n- type: business\n  text: you agree to provide Blink accurate and complete information about you and your business\nrestricted_uses:\n- summary: Personal use of BlinkRx prescriptions\n  text: You agree that any prescriptions that you purchase through BlinkRx will be solely for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Blink may contact you to verify your Account information or request further information from you, and you\n    agree to provide such further information to ensure that you have not fraudulently created your Account.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/blink-health/eligibility/blink-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Blink Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Prescriptions
- Digital Health
- Medication
- Health Tech
---
