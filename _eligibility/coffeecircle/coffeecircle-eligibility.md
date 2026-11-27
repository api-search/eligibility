---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    - AT
    - CH
    - FR
    text: 'The Seller only delivers to customers who have their habitual residence (billing address) in one of the following countries and can provide a delivery address in the same country: Germany, Austria, Switzerland, France.'
  entity_types:
  - text: any natural person who concludes a legal transaction for a purpose that cannot be ascribed to either a commercial or independent professional activity
    type: individual
  - text: Buyers can be both consumers and entrepreneurs.
    type: business
  minimum_age:
    text: Participation requires a customer account with the Seller and that the customer has reached the age of 18.
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
name: Coffeecircle
provenance_date: '2026-11-09'
provider_name: Coffeecircle
provider_slug: coffeecircle
slug: coffeecircle-eligibility
source_date: '2026-11-09'
source_filename: coffeecircle-eligibility.yml
source_heading: Eligibility
source_page: https://www.coffeecircle.com/en/e/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coffeecircle\naid: coffeecircle\nurl: https://www.coffeecircle.com/en/e/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  - AT\n  - CH\n  - FR\n  excluded: []\n  text: 'The Seller only delivers to customers who have their habitual residence (billing address) in one of the\n    following countries and can provide a delivery address in the same country: Germany, Austria, Switzerland, France.'\nentity_types:\n- type: individual\n  text: any natural person who concludes a legal transaction for a purpose that cannot be ascribed to either a commercial\n    or independent professional activity\n- type:\
  \ business\n  text: Buyers can be both consumers and entrepreneurs.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Participation requires a customer account with the Seller and that the customer has reached the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/coffeecircle/eligibility/coffeecircle-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Coffeecircle's own page on 2026-11-09.
synthetic: false
tags:
- Coffee
- Retail
- E-Commerce
- Sustainability
- Direct Trade
---
