---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Disclosure of identifying information
    text: Willfully disclosing any information that could identify a person or establishment in any manner to a person or agency not entitled to receive it, shall be guilty of a class E felony and imprisoned for not more than 5 years, or fined not more than $250,000, or both.
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
name: NHANES (CDC)
provenance_date: '2026-11-10'
provider_name: NHANES (CDC)
provider_slug: nhanes
slug: nhanes-eligibility
source_date: '2026-11-10'
source_filename: nhanes-eligibility.yml
source_heading: Eligibility
source_page: https://www.cdc.gov/nchs/policy/data-user-agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NHANES (CDC)\naid: nhanes\nurl: https://www.cdc.gov/nchs/policy/data-user-agreement.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Disclosure of identifying information\n  text: Willfully disclosing any information that could identify a person or establishment in any manner to a person\n    or agency not entitled to receive it, shall be guilty of a class E felony and imprisoned for not more than 5\n    years, or fined not more than $250,000, or both.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nhanes/eligibility/nhanes-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from NHANES (CDC)'s own page on 2026-11-10.
synthetic: false
tags:
- Public Health
- Health Statistics
- Nutrition
- Open Data
- Survey Data
- Government
- CDC
---
