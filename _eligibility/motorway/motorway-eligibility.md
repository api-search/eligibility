---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: We make this Platform, including any offer or promotion of any Service, available for United Kingdom residents only
  entity_types:
  - text: private individuals wishing to sell a car on their own behalf or on behalf of someone else in respect of whom they are legally authorised to act
    type: individual
  minimum_age:
    text: By submitting your details and so creating an account with us, you confirm that you are over 18 years old
    value: '18'
  restricted_uses:
  - summary: No business or commercial valuation use
    text: It is strictly prohibited to use the valuation tool on our Platform and the valuations provided for any business or commercial purposes, unless expressly permitted by us in writing.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We will ask you to upload certain documentation to (a) verify your ownership of, and/or right to sell the vehicle, (b) confirm your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Motorway
provenance_date: '2026-11-10'
provider_name: Motorway
provider_slug: motorway
slug: motorway-eligibility
source_date: '2026-11-10'
source_filename: motorway-eligibility.yml
source_heading: Eligibility
source_page: https://motorway.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motorway\naid: motorway\nurl: https://motorway.co.uk/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: We make this Platform, including any offer or promotion of any Service, available for United Kingdom residents\n    only\nentity_types:\n- type: individual\n  text: private individuals wishing to sell a car on their own behalf or on behalf of someone else in respect of\n    whom they are legally authorised to act\nrestricted_uses:\n- summary: No business or commercial valuation use\n  text: It is strictly prohibited to use the valuation tool on our Platform and the valuations\
  \ provided for any\n    business or commercial purposes, unless expressly permitted by us in writing.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We will ask you to upload certain documentation to (a) verify your ownership of, and/or right to sell the\n    vehicle, (b) confirm your identity\nminimum_age:\n  value: '18'\n  text: By submitting your details and so creating an account with us, you confirm that you are over 18 years old\n"
source_yaml_url: https://artifacts.apis.io/motorway/eligibility/motorway-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Motorway's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Automotive
- Used Cars
- Car Auction
- Vehicle Valuation
- Payments
---
