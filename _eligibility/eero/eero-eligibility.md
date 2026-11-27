---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'These Terms of Service apply to the following countries/territories: Bahamas Bermuda Canada Costa Rica Commonwealth of the Northern Mariana Islands (CNMI) Guam Honduras Mexico Panama Puerto Rico United States'
  entity_types:
  - text: You represent that you are at least 18 years old
    type: individual
  - text: or the company you represent (if accessing as a business)
    type: business
  minimum_age:
    text: You represent that you are at least 18 years old and not a person or legal entity barred from using the Products
    value: '18'
  restricted_uses:
  - summary: High-risk applications prohibited
    text: You may not use or permit any third party to use the Products in connection with any High Risk Activities.
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
name: Eero
provenance_date: '2026-11-09'
provider_name: Eero
provider_slug: eero
slug: eero-eligibility
source_date: '2026-11-09'
source_filename: eero-eligibility.yml
source_heading: Eligibility
source_page: https://eero.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eero\naid: eero\nurl: https://eero.com/legal/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'These Terms of Service apply to the following countries/territories: Bahamas Bermuda Canada Costa Rica\n    Commonwealth of the Northern Mariana Islands (CNMI) Guam Honduras Mexico Panama Puerto Rico United States'\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years old\n- type: business\n  text: or the company you represent (if accessing as a business)\nrestricted_uses:\n- summary: High-risk applications prohibited\n  text: You may not use or permit\
  \ any third party to use the Products in connection with any High Risk Activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years old and not a person or legal entity barred from using the\n    Products\n"
source_yaml_url: https://artifacts.apis.io/eero/eligibility/eero-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Eero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Networking
- Wi-Fi
- Mesh Networking
- Home Networking
- Smart Home
- IoT
- Hardware
- Consumer Electronics
---
