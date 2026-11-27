---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You agree not to attempt to log on to the Site from any country under sanctions by the Office of Foreign Asset Control (“OFAC”).
  entity_types:
  - text: The Site, and the products and services described on the Site, are intended for use for individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: intended for use for individuals who are at least 13 years old
    value: '13'
  restricted_uses:
  - summary: OFAC-sanctioned countries
    text: You agree not to attempt to log on to the Site from any country under sanctions by the Office of Foreign Asset Control (“OFAC”).
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility for the products and services listed on the Site are subject to the final approval and acceptance of Leap Finance or other third party offering the product or service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Leap Finance
provenance_date: '2026-11-09'
provider_name: Leap Finance
provider_slug: leap-finance
slug: leap-finance-eligibility
source_date: '2026-11-09'
source_filename: leap-finance-eligibility.yml
source_heading: Eligibility
source_page: https://leapfinance.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leap Finance\naid: leap-finance\nurl: https://leapfinance.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You agree not to attempt to log on to the Site from any country under sanctions by the Office of Foreign\n    Asset Control (“OFAC”).\nentity_types:\n- type: individual\n  text: The Site, and the products and services described on the Site, are intended for use for individuals who\n    are at least 13 years old.\nrestricted_uses:\n- summary: OFAC-sanctioned countries\n  text: You agree not to attempt to log on to the Site from any country under sanctions by the Office\
  \ of Foreign\n    Asset Control (“OFAC”).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your eligibility for the products and services listed on the Site are subject to the final approval and\n    acceptance of Leap Finance or other third party offering the product or service.\nminimum_age:\n  value: '13'\n  text: intended for use for individuals who are at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/leap-finance/eligibility/leap-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Leap Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Lending
- Student Loans
- Education Finance
- Fintech
- Consumer Finance
- Study Abroad
- India
---
