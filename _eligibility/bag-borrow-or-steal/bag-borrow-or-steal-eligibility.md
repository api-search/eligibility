---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: FREE Standard Shipping on all orders within the United States. Only U.S. mobile numbers are eligible to participate.
  entity_types:
  - text: You must be 18 years of age or older to register as a member and use the Service.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older to register as a member and use the Service.
    value: '18'
  restricted_uses:
  - summary: Resellers cannot use trademarks
    text: (c) Resellers cannot use the Bag Borrow or Steal trademarks
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Typically this is done when requesting a "Credit Check Required" item HOWEVER we reserve the right to perform this at any time an order is placed.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bag Borrow or Steal
provenance_date: '2026-11-09'
provider_name: Bag Borrow or Steal
provider_slug: bag-borrow-or-steal
slug: bag-borrow-or-steal-eligibility
source_date: '2026-11-09'
source_filename: bag-borrow-or-steal-eligibility.yml
source_heading: Eligibility
source_page: https://www.bagborroworsteal.com/termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bag Borrow or Steal\naid: bag-borrow-or-steal\nurl: https://www.bagborroworsteal.com/termsandconditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: FREE Standard Shipping on all orders within the United States. Only U.S. mobile numbers are eligible to\n    participate.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to register as a member and use the Service.\nrestricted_uses:\n- summary: Resellers cannot use trademarks\n  text: (c) Resellers cannot use the Bag Borrow or Steal trademarks\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Typically this is done when requesting a \"Credit Check Required\" item HOWEVER we reserve the right to perform\n    this at any time an order is placed.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to register as a member and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bag-borrow-or-steal/eligibility/bag-borrow-or-steal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bag Borrow or Steal's own page on 2026-11-09.
synthetic: false
tags:
- Handbags
- Rentals
- Authentication
- Accessories
---
