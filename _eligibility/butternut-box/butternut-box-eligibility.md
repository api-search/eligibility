---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: We sell to the United Kingdom (including Northern Ireland).
  entity_types:
  - text: Our Site is only intended for users over the age of 18.
    type: individual
  minimum_age:
    text: By registering an Account with us, you are confirming that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: We only supply the products for domestic and private use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to purchase products from the Site, you must have correct, accurate and valid payment card details entered on your Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Butternut Box
provenance_date: '2026-11-09'
provider_name: Butternut Box
provider_slug: butternut-box
slug: butternut-box-eligibility
source_date: '2026-11-09'
source_filename: butternut-box-eligibility.yml
source_heading: Eligibility
source_page: https://butternutbox.com/terms-and-conditions/2025
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Butternut Box\naid: butternut-box\nurl: https://butternutbox.com/terms-and-conditions/2025\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: We sell to the United Kingdom (including Northern Ireland).\nentity_types:\n- type: individual\n  text: Our Site is only intended for users over the age of 18.\nrestricted_uses:\n- summary: Domestic and private use only\n  text: We only supply the products for domestic and private use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to purchase products from the Site, you must have correct, accurate and\
  \ valid payment card details\n    entered on your Account.\nminimum_age:\n  value: '18'\n  text: By registering an Account with us, you are confirming that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/butternut-box/eligibility/butternut-box-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Butternut Box's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pet Care
- Pet Food
- Direct to Consumer
- Subscription
- E-Commerce
- Food and Beverage
- Consumer Goods
- United Kingdom
---
