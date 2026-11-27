---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: To register an account or to use the Website you must be at least 18 years old, have a current Australian residential address and have capacity to enter into a legally binding agreement with us.
  entity_types:
  - text: You warrant that you have legal capacity to enter into a legally binding contract and are 18 years or older.
    type: individual
  - text: Purchaser means a person or company purchasing a Car from Carma;
    type: business
  minimum_age:
    text: To register an account or to use the Website you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unauthorised access interference
    text: 'You must not: interfere (or attempt to interfere) or disrupt (or attempt to disrupt) our Website or the servers or networks that host our Website;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Upon Delivery of the Car, you must provide your photographic Australian driving licence (or similar form of identification) to the Carma delivery provider to verify your identity against the name specified in the Contract of Sale.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carma
provenance_date: '2026-11-09'
provider_name: Carma
provider_slug: carma
slug: carma-eligibility
source_date: '2026-11-09'
source_filename: carma-eligibility.yml
source_heading: Eligibility
source_page: https://carma.com.au/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carma\naid: carma\nurl: https://carma.com.au/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: To register an account or to use the Website you must be at least 18 years old, have a current Australian\n    residential address and have capacity to enter into a legally binding agreement with us.\nentity_types:\n- type: individual\n  text: You warrant that you have legal capacity to enter into a legally binding contract and are 18 years or older.\n- type: business\n  text: Purchaser means a person or company purchasing a Car from Carma;\nrestricted_uses:\n- summary:\
  \ Unauthorised access interference\n  text: 'You must not: interfere (or attempt to interfere) or disrupt (or attempt to disrupt) our Website or the\n    servers or networks that host our Website;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Upon Delivery of the Car, you must provide your photographic Australian driving licence (or similar form\n    of identification) to the Carma delivery provider to verify your identity against the name specified in the\n    Contract of Sale.\nminimum_age:\n  value: '18'\n  text: To register an account or to use the Website you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/carma/eligibility/carma-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Carma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Automotive
- Used Cars
- Marketplace
- E-Commerce
- Car Finance
- Australia
---
