---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into legally binding contracts
    type: individual
  - text: If you are registering an Account for a company or other legal entity, you represent and warrant that you have the authority to legally bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into legally binding contracts
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: The Good Dog Platform may only be used for lawful purposes by Buyers seeking dogs and Breeders seeking to market and sell dogs.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may, but have no obligation to, (i) ask Members to provide a form of government identification or other information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Good Dog
provenance_date: '2026-11-09'
provider_name: Good Dog
provider_slug: gooddog
slug: gooddog-eligibility
source_date: '2026-11-09'
source_filename: gooddog-eligibility.yml
source_heading: Eligibility
source_page: https://www.gooddog.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Good Dog\naid: gooddog\nurl: https://www.gooddog.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into legally binding contracts\n- type: business\n  text: If you are registering an Account for a company or other legal entity, you represent and warrant that you\n    have the authority to legally bind that entity\nrestricted_uses:\n- summary: Lawful purposes only\n  text: The Good Dog Platform may only be used for lawful purposes by Buyers seeking\
  \ dogs and Breeders seeking to\n    market and sell dogs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may, but have no obligation to, (i) ask Members to provide a form of government identification or other\n    information\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into legally binding contracts\n"
source_yaml_url: https://artifacts.apis.io/gooddog/eligibility/gooddog-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Good Dog's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Pets
- Dogs
- Breeders
- Animal Welfare
- Consumer
- Payments
- Pet Insurance
---
