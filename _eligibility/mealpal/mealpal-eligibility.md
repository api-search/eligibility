---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: MealPal, Inc. for members in the United States and MealPal Canada Limited for members in Canada
  entity_types:
  - text: Your MealPal membership is personal to you and not for the use or benefit of any third party
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: No commercial purposes
    text: MealPal may not be used for commercial purposes.
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
name: MealPal
provenance_date: '2026-11-10'
provider_name: MealPal
provider_slug: mealpal
slug: mealpal-eligibility
source_date: '2026-11-10'
source_filename: mealpal-eligibility.yml
source_heading: Eligibility
source_page: https://www.mealpal.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MealPal\naid: mealpal\nurl: https://www.mealpal.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: MealPal, Inc. for members in the United States and MealPal Canada Limited for members in Canada\nentity_types:\n- type: individual\n  text: Your MealPal membership is personal to you and not for the use or benefit of any third party\nrestricted_uses:\n- summary: No commercial purposes\n  text: MealPal may not be used for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: you represent and warrant that you are at least 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/mealpal/eligibility/mealpal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MealPal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Food
- Meal Subscription
- Restaurant
- Mobile App
---
