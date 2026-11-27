---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Datasembly reserves the right (without undertaking any duty) to use “geo-filtering” or other technologies to block access to certain jurisdictions, in its sole discretion, without notice.
  entity_types:
  - text: By using the Services, you warrant that you are at least eighteen (18) years old and have the legal capacity to enter into binding contracts.
    type: individual
  minimum_age:
    text: you warrant that you are at least eighteen (18) years old and have the legal capacity to enter into binding contracts
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You agree that it will not directly or indirectly, export, re-export, import, or otherwise transfer the Data or related information, media, or products outside of the United States or in violation of any applicable laws
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
name: Datasembly
provenance_date: '2026-11-09'
provider_name: Datasembly
provider_slug: datasembly
slug: datasembly-eligibility
source_date: '2026-11-09'
source_filename: datasembly-eligibility.yml
source_heading: Eligibility
source_page: https://datasembly.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datasembly\naid: datasembly\nurl: https://datasembly.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Datasembly reserves the right (without undertaking any duty) to use “geo-filtering” or other technologies\n    to block access to certain jurisdictions, in its sole discretion, without notice.\nentity_types:\n- type: individual\n  text: By using the Services, you warrant that you are at least eighteen (18) years old and have the legal capacity\n    to enter into binding contracts.\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree that it will not directly\
  \ or indirectly, export, re-export, import, or otherwise transfer the\n    Data or related information, media, or products outside of the United States or in violation of any applicable\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you warrant that you are at least eighteen (18) years old and have the legal capacity to enter into binding\n    contracts\n"
source_yaml_url: https://artifacts.apis.io/datasembly/eligibility/datasembly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Datasembly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Grocery
- Pricing
- Data
- Analytics
- Consumer Packaged Goods
- Market Intelligence
- Competitive Intelligence
---
