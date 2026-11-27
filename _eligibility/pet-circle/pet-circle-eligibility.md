---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be over the age of 18 years and/or able to enter into a legally binding contract to use the Website.
    type: individual
  minimum_age:
    text: You must be over the age of 18 years and/or able to enter into a legally binding contract to use the Website.
    value: '18'
  restricted_uses:
  - summary: Discount codes not for prescription medication
    text: Cannot be used for Prescription Medication or any item found on petcirclepharma.com.au
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
name: Pet Circle
provenance_date: '2026-11-10'
provider_name: Pet Circle
provider_slug: pet-circle
slug: pet-circle-eligibility
source_date: '2026-11-10'
source_filename: pet-circle-eligibility.yml
source_heading: Eligibility
source_page: https://www.petcircle.com.au/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pet Circle\naid: pet-circle\nurl: https://www.petcircle.com.au/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be over the age of 18 years and/or able to enter into a legally binding contract to use the Website.\nrestricted_uses:\n- summary: Discount codes not for prescription medication\n  text: Cannot be used for Prescription Medication or any item found on petcirclepharma.com.au\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be\
  \ over the age of 18 years and/or able to enter into a legally binding contract to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/pet-circle/eligibility/pet-circle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pet Circle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Pets
- Consumer
- Australia
- Direct to Consumer
- Pet Supplies
- Headless Commerce
---
