---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - RU
    - BY
    - SY
    served: []
    text: not be located in, under the control of, or resident in any sanctioned or embargoed jurisdiction (including Crimea, Cuba, Donetsk, Iran, Luhansk, North Korea, Russia, Belarus, and Syria
  entity_types:
  - text: To use EMMA you must be 18 years old or older
    type: individual
  minimum_age:
    text: To use EMMA you must be 18 years old or older
    value: '18'
  restricted_uses:
  - summary: Not medical or psychological service
    text: EMMA is not a medical or psychological service and should not be used as a substitute for professional medical, psychological, legal, financial, or other expert services.
  - summary: Personal use only
    text: The App is intended for personal, non-commercial use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- RU
- BY
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Emma
provenance_date: '2026-11-09'
provider_name: Emma
provider_slug: emma
slug: emma-eligibility
source_date: '2026-11-09'
source_filename: emma-eligibility.yml
source_heading: Eligibility
source_page: https://emma-learn.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Emma\naid: emma\nurl: https://emma-learn.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - RU\n  - BY\n  - SY\n  text: not be located in, under the control of, or resident in any sanctioned or embargoed jurisdiction (including\n    Crimea, Cuba, Donetsk, Iran, Luhansk, North Korea, Russia, Belarus, and Syria\nentity_types:\n- type: individual\n  text: To use EMMA you must be 18 years old or older\nrestricted_uses:\n- summary: Not medical or psychological service\n  text: EMMA is not a medical or psychological service and should not be used as a substitute\
  \ for professional medical,\n    psychological, legal, financial, or other expert services.\n- summary: Personal use only\n  text: The App is intended for personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use EMMA you must be 18 years old or older\n"
source_yaml_url: https://artifacts.apis.io/emma/eligibility/emma-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Emma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Language Learning
- English Learning
- Artificial Intelligence
- Mobile App
- Conversation Practice
- Consumer
---
