---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: These Terms and Conditions are void where prohibited by law.
  entity_types:
  - text: the Application is offered only for your use, and not for the use or benefit of any third party.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Health and physician approval
    text: The Application is only intended for use by individuals healthy enough to perform strenuous exercises.
  - summary: Pregnancy or lactation
    text: If applicable, you further affirm that (A) you are not pregnant, breastfeeding or lactating, or (B) your physician has specifically approved your use of the Application.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GymNadz
provenance_date: '2026-11-09'
provider_name: GymNadz
provider_slug: gymnadz
slug: gymnadz-eligibility
source_date: '2026-11-09'
source_filename: gymnadz-eligibility.yml
source_heading: Eligibility
source_page: https://gymnadz.com/terms-conditions-en/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GymNadz\naid: gymnadz\nurl: https://gymnadz.com/terms-conditions-en/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: These Terms and Conditions are void where prohibited by law.\nentity_types:\n- type: individual\n  text: the Application is offered only for your use, and not for the use or benefit of any third party.\nrestricted_uses:\n- summary: Health and physician approval\n  text: The Application is only intended for use by individuals healthy enough to perform strenuous exercises.\n- summary: Pregnancy or lactation\n  text: If applicable, you further affirm that (A) you are\
  \ not pregnant, breastfeeding or lactating, or (B) your\n    physician has specifically approved your use of the Application.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gymnadz/eligibility/gymnadz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from GymNadz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fitness
- Health
- Wellness
- Mobile
- Nutrition
- Women
- Consumer App
---
