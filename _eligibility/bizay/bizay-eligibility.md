---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Register on the website, creating a unique profile in your own name
    type: individual
  - text: creating a unique profile in your own name or on behalf of a legal person as long as you have powers to do so
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, offensive or harmful use
    text: You agree that you will not use this website to produce offensive, illegal, malicious, harmful, or any other action that violates the rights of other individuals, trademarks, or companies.
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
name: Bizay
provenance_date: '2026-11-09'
provider_name: Bizay
provider_slug: bizay
slug: bizay-eligibility
source_date: '2026-11-09'
source_filename: bizay-eligibility.yml
source_heading: Eligibility
source_page: https://us.bizay.com/en-us/Home/TermsAndConditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bizay\naid: bizay\nurl: https://us.bizay.com/en-us/Home/TermsAndConditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Register on the website, creating a unique profile in your own name\n- type: business\n  text: creating a unique profile in your own name or on behalf of a legal person as long as you have powers to\n    do so\nrestricted_uses:\n- summary: Illegal, offensive or harmful use\n  text: You agree that you will not use this website to produce offensive, illegal, malicious, harmful, or any other\n    action that violates\
  \ the rights of other individuals, trademarks, or companies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bizay/eligibility/bizay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bizay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Print on Demand
- Marketing
- Customization
---
