---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Each licensed retailer will only sell and deliver in the state in which it is licensed.
  entity_types:
  - text: If you're contracting as a consumer, you may cancel your membership or the purchase of an item other than an alcoholic beverage at any time in accordance with our Refund Policy
    type: individual
  minimum_age:
    text: You have to be over 21 to enter this site.
    value: '21'
  restricted_uses:
  - summary: Personal consumption only
    text: Your order is intended for personal consumption and not for sampling or resale purposes.
  - summary: No resale or illegal use
    text: Use of our products is for personal use only and can not be used for any illegal or unauthorized purpose.
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
name: Flaviar
provenance_date: '2026-11-09'
provider_name: Flaviar
provider_slug: flaviar
slug: flaviar-eligibility
source_date: '2026-11-09'
source_filename: flaviar-eligibility.yml
source_heading: Eligibility
source_page: https://flaviar.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flaviar\naid: flaviar\nurl: https://flaviar.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Each licensed retailer will only sell and deliver in the state in which it is licensed.\nentity_types:\n- type: individual\n  text: If you're contracting as a consumer, you may cancel your membership or the purchase of an item other than\n    an alcoholic beverage at any time in accordance with our Refund Policy\nrestricted_uses:\n- summary: Personal consumption only\n  text: Your order is intended for personal consumption and not for sampling or resale purposes.\n\
  - summary: No resale or illegal use\n  text: Use of our products is for personal use only and can not be used for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: You have to be over 21 to enter this site.\n"
source_yaml_url: https://artifacts.apis.io/flaviar/eligibility/flaviar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Flaviar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Spirits
- Whiskey
- E-Commerce
- Retail
- Beverages
- Subscription
- Agentic Commerce
- Shopify
---
