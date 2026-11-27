---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Sites, you represent and warrant that you (a) are 18 years of age or older
    type: individual
  minimum_age:
    text: The Sites are not targeted toward or intended for use by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Resale or commercial use of products
    text: You are not permitted to resell or otherwise use the Products for commercial purposes.
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
name: CraftCoffee
provenance_date: '2026-11-09'
provider_name: CraftCoffee
provider_slug: craftcoffee
slug: craftcoffee-eligibility
source_date: '2026-11-09'
source_filename: craftcoffee-eligibility.yml
source_heading: Eligibility
source_page: https://www.craftcoffee.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CraftCoffee\naid: craftcoffee\nurl: https://www.craftcoffee.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Sites, you represent and warrant that you (a) are 18 years of age or older\nrestricted_uses:\n- summary: Resale or commercial use of products\n  text: You are not permitted to resell or otherwise use the Products for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Sites are not targeted toward\
  \ or intended for use by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/craftcoffee/eligibility/craftcoffee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CraftCoffee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coffee
- Coffee Subscription
- Direct to Consumer
- E-Commerce
- Food and Beverage
- Subscription Commerce
- Retail
---
