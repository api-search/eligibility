---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Creating an account or purchasing a subscription requires an adult over 18.
    type: individual
  - text: We will not be liable to you for any losses that you may suffer if you have used the App for business purposes.
    type: business
  minimum_age:
    text: creating an account or purchasing a subscription requires an adult over 18.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You will not use the App for any commercial purposes without our prior written permission
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
name: Mind Candy, Moshi
provenance_date: '2026-11-10'
provider_name: Mind Candy, Moshi
provider_slug: mind-candy-moshi
slug: mind-candy-moshi-eligibility
source_date: '2026-11-10'
source_filename: mind-candy-moshi-eligibility.yml
source_heading: Eligibility
source_page: https://www.moshikids.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mind Candy, Moshi\naid: mind-candy-moshi\nurl: https://www.moshikids.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Creating an account or purchasing a subscription requires an adult over 18.\n- type: business\n  text: We will not be liable to you for any losses that you may suffer if you have used the App for business purposes.\nrestricted_uses:\n- summary: No commercial use\n  text: You will not use the App for any commercial purposes without our prior written permission\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: creating an account or purchasing a subscription requires an adult over 18.\n"
source_yaml_url: https://artifacts.apis.io/mind-candy-moshi/eligibility/mind-candy-moshi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mind Candy, Moshi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Children
- Education
- Sleep
- Mobile App
- Subscription
- Media
---
