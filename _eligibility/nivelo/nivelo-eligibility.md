---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may utilize the Site only if you are over the age of eighteen (18) and are capable of entering into contracts.
    type: individual
  - text: BY ACCESSING OR USING THE SITE, YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: No commercial exploitation
    text: you shall not license, sell, rent, lease, transfer, assign, distribute, host, or otherwise commercially exploit the Site
  - summary: No competing products
    text: you shall not access the Site in order to build a similar or competitive website, product, or service
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
name: Nivelo
provenance_date: '2026-11-10'
provider_name: Nivelo
provider_slug: nivelo
slug: nivelo-eligibility
source_date: '2026-11-10'
source_filename: nivelo-eligibility.yml
source_heading: Eligibility
source_page: https://nivelo.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nivelo\naid: nivelo\nurl: https://nivelo.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may utilize the Site only if you are over the age of eighteen (18) and are capable of entering into\n    contracts.\n- type: business\n  text: BY ACCESSING OR USING THE SITE, YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT\n    YOU REPRESENT)\nrestricted_uses:\n- summary: No commercial exploitation\n  text: you shall not license, sell, rent, lease, transfer, assign, distribute, host, or otherwise commercially\n\
  \    exploit the Site\n- summary: No competing products\n  text: you shall not access the Site in order to build a similar or competitive website, product, or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/nivelo/eligibility/nivelo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nivelo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- ACH
- Fintech
- Payroll
- Risk Management
- Fraud Prevention
- Money Movement
- Real-Time Payments
- Treasury
- FedNow
- RTP
---
