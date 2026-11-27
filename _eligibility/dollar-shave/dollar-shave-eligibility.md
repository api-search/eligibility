---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access the DSC Services from outside the United States, you do so at your own risk and are responsible for compliance with the laws of your jurisdiction.
  entity_types:
  - text: You must be 18 years of age or older to visit or use the DSC Services in any manner.
    type: individual
  - text: You may not purchase Products or Subscriptions for further distribution or resale or for any other commercial or business purpose.
    type: business
  minimum_age:
    text: You must be 18 years of age or older to visit or use the DSC Services in any manner.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use of Products
    text: Products are only for Members’ own personal, non-commercial use.
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
name: Dollar Shave
provenance_date: '2026-11-09'
provider_name: Dollar Shave
provider_slug: dollar-shave
slug: dollar-shave-eligibility
source_date: '2026-11-09'
source_filename: dollar-shave-eligibility.yml
source_heading: Eligibility
source_page: https://ask.dollarshaveclub.com/en-US/terms-of-service-195938
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dollar Shave\naid: dollar-shave\nurl: https://ask.dollarshaveclub.com/en-US/terms-of-service-195938\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access the DSC Services from outside the United States, you do so at your own risk and are responsible\n    for compliance with the laws of your jurisdiction.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to visit or use the DSC Services in any manner.\n- type: business\n  text: You may not purchase Products or Subscriptions for further distribution or resale or for any other commercial\n    or\
  \ business purpose.\nrestricted_uses:\n- summary: Personal, non-commercial use of Products\n  text: Products are only for Members’ own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to visit or use the DSC Services in any manner.\n"
source_yaml_url: https://artifacts.apis.io/dollar-shave/eligibility/dollar-shave-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Dollar Shave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Retail
- Subscription
- Grooming
- Personal Care
- Direct to Consumer
- Shopify
---
