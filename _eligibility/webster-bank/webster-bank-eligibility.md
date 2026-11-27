---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website is offered and available to users who reside in the United States or any of its territories or possessions.
  entity_types:
  - text: you represent and warrant that you are of legal age and have the capacity to enter into a binding contract
    type: individual
  minimum_age:
    text: you represent and warrant that you are of legal age
    value: null
  restricted_uses:
  - summary: No login from OFAC-sanctioned countries
    text: You agree not to attempt to log on to the Website from any country under sanctions by the Office of Foreign Assets Control (OFAC).
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
name: Webster Bank
provenance_date: '2026-11-10'
provider_name: Webster Bank
provider_slug: webster-bank
slug: webster-bank-eligibility
source_date: '2026-11-10'
source_filename: webster-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.websterbank.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Webster Bank\naid: webster-bank\nurl: https://www.websterbank.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website is offered and available to users who reside in the United States or any of its territories\n    or possessions.\nentity_types:\n- type: individual\n  text: you represent and warrant that you are of legal age and have the capacity to enter into a binding contract\nrestricted_uses:\n- summary: No login from OFAC-sanctioned countries\n  text: You agree not to attempt to log on to the Website from any country under sanctions by the Office of Foreign\n\
  \    Assets Control (OFAC).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age\n"
source_yaml_url: https://artifacts.apis.io/webster-bank/eligibility/webster-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Webster Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Commercial Banking
- Super-Regional Bank
- Open Finance
- FDX
- Health Savings
---
