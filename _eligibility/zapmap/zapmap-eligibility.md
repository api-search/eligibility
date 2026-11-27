---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You may not use the Website, App or Services if: 4.5.1 you are located in a country which is subject to any UK, EU, or US sanctions or embargo which impacts the Website, App or Services or the use of similar services'
  entity_types:
  - text: The Website, App and Services may only be used by individuals or authorised representatives of businesses, organisations or legal entities in good standing
    type: individual
  - text: authorised representatives of businesses, organisations or legal entities in good standing (and which possess the ability to enter into legally binding contracts)
    type: business
  minimum_age:
    text: You may only use the App or Services if you are old enough to drive legally in the country in which that use occurs.
    value: legal driving age
  restricted_uses:
  - summary: Fraudulent or unlawful use
    text: use the Website, App or Services in a fraudulent or malicious way, or in any way which is unlawful or in breach of these terms of use
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
name: Zapmap
provenance_date: '2026-11-10'
provider_name: Zapmap
provider_slug: zapmap
slug: zapmap-eligibility
source_date: '2026-11-10'
source_filename: zapmap-eligibility.yml
source_heading: Eligibility
source_page: https://www.zapmap.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zapmap\naid: zapmap\nurl: https://www.zapmap.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'You may not use the Website, App or Services if: 4.5.1 you are located in a country which is subject to\n    any UK, EU, or US sanctions or embargo which impacts the Website, App or Services or the use of similar services'\nentity_types:\n- type: individual\n  text: The Website, App and Services may only be used by individuals or authorised representatives of businesses,\n    organisations or legal entities in good standing\n- type: business\n  text: authorised\
  \ representatives of businesses, organisations or legal entities in good standing (and which possess\n    the ability to enter into legally binding contracts)\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: use the Website, App or Services in a fraudulent or malicious way, or in any way which is unlawful or in\n    breach of these terms of use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal driving age\n  text: You may only use the App or Services if you are old enough to drive legally in the country in which that\n    use occurs.\n"
source_yaml_url: https://artifacts.apis.io/zapmap/eligibility/zapmap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Zapmap's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- EV Charging
- Electric Vehicles
- Charge Point Data
- Mobility
- Open Data
- Utilities
- Payments
- Route Planning
---
