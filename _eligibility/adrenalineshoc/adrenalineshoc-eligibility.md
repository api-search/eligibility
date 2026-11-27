---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company controls and operates this Site from its headquarters in the United States of America and our Content may not be appropriate or available for use in other locations.
  entity_types:
  - text: you are at least the age of majority in the jurisdiction where you reside, or if you are under the age of majority but are at least 16 years old
    type: individual
  minimum_age:
    text: or if you are under the age of majority but are at least 16 years old (a “Minor”)
    value: '16'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: the Company administrator shall have the right to approve or reject your request (or registration if applicable), in the Company administrator’s sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Adrenaline Shoc
provenance_date: '2026-11-09'
provider_name: Adrenaline Shoc
provider_slug: adrenalineshoc
slug: adrenalineshoc-eligibility
source_date: '2026-11-09'
source_filename: adrenalineshoc-eligibility.yml
source_heading: Eligibility
source_page: https://www.drinkaccelerator.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adrenaline Shoc\naid: adrenalineshoc\nurl: https://www.drinkaccelerator.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company controls and operates this Site from its headquarters in the United States of America and our\n    Content may not be appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are at least the age of majority in the jurisdiction where you reside, or if you are under the age of\n    majority but are at least 16 years old\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: true\n  text: the Company administrator shall have the right to approve or reject your request (or registration if applicable),\n    in the Company administrator’s sole discretion.\nminimum_age:\n  value: '16'\n  text: or if you are under the age of majority but are at least 16 years old (a “Minor”)\n"
source_yaml_url: https://artifacts.apis.io/adrenalineshoc/eligibility/adrenalineshoc-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Adrenaline Shoc's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beverages
- Energy Drinks
- Consumer Packaged Goods
- Retail
- E-Commerce
- Direct to Consumer
- Agentic Commerce
- Shopify
- Sports Nutrition
---
