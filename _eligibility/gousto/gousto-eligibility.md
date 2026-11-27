---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where we refer to “Consumer” below we mean an individual acting for purposes which are wholly or mainly outside that person’s trade, business, craft or profession.
    type: individual
  minimum_age:
    text: By placing an order, you are confirming that you are 18 years of age or older and that the supply of alcohol shall not be to anyone under the age of 18 years of age.
    value: '18'
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
name: Gousto
provenance_date: '2026-11-09'
provider_name: Gousto
provider_slug: gousto
slug: gousto-eligibility
source_date: '2026-11-09'
source_filename: gousto-eligibility.yml
source_heading: Eligibility
source_page: https://www.gousto.co.uk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gousto\naid: gousto\nurl: https://www.gousto.co.uk/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Where we refer to “Consumer” below we mean an individual acting for purposes which are wholly or mainly\n    outside that person’s trade, business, craft or profession.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By placing an order, you are confirming that you are 18 years of age or older and that the supply of alcohol\n\
  \    shall not be to anyone under the age of 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/gousto/eligibility/gousto-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Gousto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Meal Kit
- Food Delivery
- E-Commerce
- Subscription
- United Kingdom
---
