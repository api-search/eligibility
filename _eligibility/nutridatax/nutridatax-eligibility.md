---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You will not use your account in a commercial fashion or manner.
    type: business
  minimum_age:
    text: The Site and the Services are intended solely for users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: No medical advice use
    text: Nothing on the NutriDataXs Site or Services should be taken as medical information or advice.
  - summary: No commercial account use
    text: You will not use your account in a commercial fashion or manner.
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
name: NutriDataX
provenance_date: '2026-11-10'
provider_name: NutriDataX
provider_slug: nutridatax
slug: nutridatax-eligibility
source_date: '2026-11-10'
source_filename: nutridatax-eligibility.yml
source_heading: Eligibility
source_page: https://nutridatax.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NutriDataX\naid: nutridatax\nurl: https://nutridatax.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You will not use your account in a commercial fashion or manner.\nrestricted_uses:\n- summary: No medical advice use\n  text: Nothing on the NutriDataXs Site or Services should be taken as medical information or advice.\n- summary: No commercial account use\n  text: You will not use your account in a commercial fashion or manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The Site and the Services are intended solely for users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/nutridatax/eligibility/nutridatax-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from NutriDataX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Nutrition
- Food Data
- Artificial Intelligence
---
