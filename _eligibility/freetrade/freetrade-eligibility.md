---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: be a UK resident for tax purposes and live in the UK;
  entity_types:
  - text: be acting in your personal capacity
    type: individual
  - text: cannot open or hold an account (i) on behalf of another person, (ii) on behalf of a business (even if it's your own business)
    type: business
  minimum_age:
    text: be at least 18 years old;
    value: '18'
  restricted_uses:
  - summary: US Person restriction
    text: not be a 'U.S. Person', as defined under the US' Foreign Account Tax Compliance Act.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must set up a customer profile with us and complete an account-opening process on our Freetrade Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Freetrade
provenance_date: '2026-11-09'
provider_name: Freetrade
provider_slug: freetrade
slug: freetrade-eligibility
source_date: '2026-11-09'
source_filename: freetrade-eligibility.yml
source_heading: Eligibility
source_page: https://freetrade.io/terms-and-conditions-2
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freetrade\naid: freetrade\nurl: https://freetrade.io/terms-and-conditions-2\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: be a UK resident for tax purposes and live in the UK;\nentity_types:\n- type: individual\n  text: be acting in your personal capacity\n- type: business\n  text: cannot open or hold an account (i) on behalf of another person, (ii) on behalf of a business (even if it's\n    your own business)\nrestricted_uses:\n- summary: US Person restriction\n  text: not be a 'U.S. Person', as defined under the US' Foreign Account Tax Compliance Act.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must set up a customer profile with us and complete an account-opening process on our Freetrade Platform.\nminimum_age:\n  value: '18'\n  text: be at least 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/freetrade/eligibility/freetrade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Freetrade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Investing
- Stock Trading
- Brokerage
- Financial Services
- Fintech
- Pensions
- ISA
- Personal Finance
- United Kingdom
---
