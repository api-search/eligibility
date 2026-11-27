---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    text: you must be 18 years or older and resident in Egypt to purchase any products or services from us.
  minimum_age:
    text: you must be 18 years or older and resident in Egypt to purchase any products or services from us.
    value: '18'
  restricted_uses:
  - summary: Commercial use of personal app
    text: we reasonably suspect you are not using the app for personal usage as a customer and you are abusing it commercially as a merchant instead.
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
name: Breadfast
provenance_date: '2026-11-09'
provider_name: Breadfast
provider_slug: breadfast
slug: breadfast-eligibility
source_date: '2026-11-09'
source_filename: breadfast-eligibility.yml
source_heading: Eligibility
source_page: https://www.breadfast.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Breadfast\naid: breadfast\nurl: https://www.breadfast.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EG\n  excluded: []\n  text: you must be 18 years or older and resident in Egypt to purchase any products or services from us.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use of personal app\n  text: we reasonably suspect you are not using the app for personal usage as a customer and you are abusing it\n    commercially as a merchant instead.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you\
  \ must be 18 years or older and resident in Egypt to purchase any products or services from us.\n"
source_yaml_url: https://artifacts.apis.io/breadfast/eligibility/breadfast-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Breadfast's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Grocery
- Quick Commerce
- Delivery
- E-Commerce
- Retail
- Fintech
- Egypt
---
