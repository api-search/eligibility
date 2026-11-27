---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: (b) are a legal resident of the United States
  entity_types:
  - text: By using the Sites, you represent and warrant that you (a) are 18 years of age or older
    type: individual
  minimum_age:
    text: The Sites are not targeted toward or intended for use by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use of Products
    text: You are not permitted to resell or otherwise use the Products for commercial purposes.
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
name: Blue Apron
provenance_date: '2026-11-09'
provider_name: Blue Apron
provider_slug: blue-apron
slug: blue-apron-eligibility
source_date: '2026-11-09'
source_filename: blue-apron-eligibility.yml
source_heading: Eligibility
source_page: https://www.blueapron.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blue Apron\naid: blue-apron\nurl: https://www.blueapron.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: (b) are a legal resident of the United States\nentity_types:\n- type: individual\n  text: By using the Sites, you represent and warrant that you (a) are 18 years of age or older\nrestricted_uses:\n- summary: No resale or commercial use of Products\n  text: You are not permitted to resell or otherwise use the Products for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The Sites are not targeted toward or intended for use by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/blue-apron/eligibility/blue-apron-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Blue Apron's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Meal Kit
- Food Delivery
- E-Commerce
- Subscription
- Groceries
---
