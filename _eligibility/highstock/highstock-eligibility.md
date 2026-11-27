---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old.
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, THEN YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO BIND SUCH ENTITY TO THE TERMS OF THIS AGREEMENT.
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal commercial activity without consent
    text: involves illegal commercial activities and/or sales without Highstock's prior written consent
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Highstock may, in its sole discretion, refuse to offer the Service to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Highstock
provenance_date: '2026-11-09'
provider_name: Highstock
provider_slug: highstock
slug: highstock-eligibility
source_date: '2026-11-09'
source_filename: highstock-eligibility.yml
source_heading: Eligibility
source_page: https://www.highstock.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Highstock\naid: highstock\nurl: https://www.highstock.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old.\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, THEN YOU REPRESENT AND WARRANT THAT YOU\n    ARE AUTHORIZED TO BIND SUCH ENTITY TO THE TERMS OF THIS AGREEMENT.\nrestricted_uses:\n- summary: Illegal commercial activity without consent\n  text: involves illegal commercial activities and/or sales without Highstock's\
  \ prior written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Highstock may, in its sole discretion, refuse to offer the Service to any person or entity and change its\n    eligibility criteria at any time.\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/highstock/eligibility/highstock-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Highstock's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Wholesale
- Inventory
- E-Commerce
- Retail
- Beauty
- B2B
- Artificial Intelligence
- Sustainability
---
