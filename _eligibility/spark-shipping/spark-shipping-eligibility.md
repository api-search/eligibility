---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To register and become a "member" of the Site, you must be 18 years of age and possess the legal right to enter into and form a legally binding contract.
    type: individual
  minimum_age:
    text: you must be 18 years of age and possess the legal right to enter into and form a legally binding contract.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: 'you hereby represent, state and pledge that you: a) are not on the list of prohibited individuals which may be identified on any government export exclusion report'
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
name: Spark Shipping
provenance_date: '2026-11-10'
provider_name: Spark Shipping
provider_slug: spark-shipping
slug: spark-shipping-eligibility
source_date: '2026-11-10'
source_filename: spark-shipping-eligibility.yml
source_heading: Eligibility
source_page: https://www.sparkshipping.com/pages/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spark Shipping\naid: spark-shipping\nurl: https://www.sparkshipping.com/pages/terms_of_service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To register and become a \"member\" of the Site, you must be 18 years of age and possess the legal right to\n    enter into and form a legally binding contract.\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: 'you hereby represent, state and pledge that you: a) are not on the list of prohibited individuals which\n    may be identified on any government export exclusion\
  \ report'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be 18 years of age and possess the legal right to enter into and form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/spark-shipping/eligibility/spark-shipping-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Spark Shipping's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Dropshipping
- Automation
- Software-as-a-Service
- Integration
---
