---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: (b) are a legal resident of the United States
  entity_types:
  - text: You may use the Services only for your own non-commercial personal use and in compliance with these Terms.
    type: individual
  minimum_age:
    text: The Services are not targeted toward or intended for use by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Alcohol purchases
    text: You must be, and by purchasing you represent, warrant, and certify that you are, at least 21 years of age to purchase any alcoholic beverages.
  - summary: Reseller orders
    text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers, or distributors.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Thrive Market
provenance_date: '2026-11-10'
provider_name: Thrive Market
provider_slug: thrive-market
slug: thrive-market-eligibility
source_date: '2026-11-10'
source_filename: thrive-market-eligibility.yml
source_heading: Eligibility
source_page: https://thrivemarket.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thrive Market\naid: thrive-market\nurl: https://thrivemarket.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: (b) are a legal resident of the United States\nentity_types:\n- type: individual\n  text: You may use the Services only for your own non-commercial personal use and in compliance with these Terms.\nrestricted_uses:\n- summary: Alcohol purchases\n  text: You must be, and by purchasing you represent, warrant, and certify that you are, at least 21 years of age\n    to purchase any alcoholic beverages.\n- summary: Reseller orders\n  text: We reserve the right to\
  \ limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers, or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.\nminimum_age:\n  value: '16'\n  text: The Services are not targeted toward or intended for use by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/thrive-market/eligibility/thrive-market-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Thrive Market's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Grocery
- Food and Beverage
- Consumer Goods
- Direct to Consumer
- Membership
- Health and Wellness
---
