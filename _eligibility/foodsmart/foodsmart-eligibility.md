---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for your personal, non-commercial purposes while this Agreement remains in effect.
    type: individual
  minimum_age:
    text: YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST 13 YEARS OF AGE
    value: '13'
  restricted_uses:
  - summary: No commercial use of the Site
    text: The End User shall not use the site for any commercial purpose under any circumstance, unless in each instance the End User has obtained explicit written approval by Foodsmart.
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
name: Foodsmart
provenance_date: '2026-11-09'
provider_name: Foodsmart
provider_slug: foodsmart
slug: foodsmart-eligibility
source_date: '2026-11-09'
source_filename: foodsmart-eligibility.yml
source_heading: Eligibility
source_page: https://foodsmart.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Foodsmart\naid: foodsmart\nurl: https://foodsmart.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: solely for your personal, non-commercial purposes while this Agreement remains in effect.\nrestricted_uses:\n- summary: No commercial use of the Site\n  text: The End User shall not use the site for any commercial purpose under any circumstance, unless in each instance\n    the End User has obtained explicit written approval by Foodsmart.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '13'\n  text: YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST 13 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/foodsmart/eligibility/foodsmart-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Foodsmart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Nutrition
- Telehealth
- Telenutrition
- Healthcare
- Dietitians
- Food Benefits
- Digital Health
- Employee Benefits
- Medicaid
---
