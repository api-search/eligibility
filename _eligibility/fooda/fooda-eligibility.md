---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are located in the United States. The Fooda SMS Programs are intended for U.S.-based mobile carriers only.
  entity_types:
  - text: You are an individual person at least 18 years of age
    type: individual
  minimum_age:
    text: You are an individual person at least 18 years of age
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Before you are authorized to be issued a Fooda Card, Fooda and Issuer must determine whether you are eligible to access and use Fooda Cards.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FoodA
provenance_date: '2026-11-09'
provider_name: FoodA
provider_slug: fooda
slug: fooda-eligibility
source_date: '2026-11-09'
source_filename: fooda-eligibility.yml
source_heading: Eligibility
source_page: https://www.fooda.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FoodA\naid: fooda\nurl: https://www.fooda.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are located in the United States. The Fooda SMS Programs are intended for U.S.-based mobile carriers\n    only.\nentity_types:\n- type: individual\n  text: You are an individual person at least 18 years of age\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Before you are authorized to be issued a Fooda Card, Fooda and Issuer must determine whether you are eligible\n    to access and use Fooda Cards.\n\
  minimum_age:\n  value: '18'\n  text: You are an individual person at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/fooda/eligibility/fooda-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from FoodA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food
- Food Service
- Workplace
- Catering
- Restaurant
- Corporate Dining
- Marketplace
---
