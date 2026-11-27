---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our Site is intended for users in the United Kingdom only.
  entity_types:
  - text: If you are a consumer, you will benefit from any mandatory provisions of the law in your country of residence.
    type: individual
  - text: If you are a business user (i.e. you are using Our Site in the course of business or for commercial purposes)
    type: business
  minimum_age:
    text: Only Users aged 18 or over may create an Account.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: You must not use Our site in any way, or for any purpose, that is unlawful or fraudulent
  - summary: Malware and unauthorised access
    text: You must not attempt to gain unauthorised access to any part of Our Site, the server on which Our Site is stored, or any other server, computer, or database connected to Our Site.
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
name: Little Freddie
provenance_date: '2026-11-09'
provider_name: Little Freddie
provider_slug: little-freddie
slug: little-freddie-eligibility
source_date: '2026-11-09'
source_filename: little-freddie-eligibility.yml
source_heading: Eligibility
source_page: https://littlefreddie.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Little Freddie\naid: little-freddie\nurl: https://littlefreddie.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our Site is intended for users in the United Kingdom only.\nentity_types:\n- type: individual\n  text: If you are a consumer, you will benefit from any mandatory provisions of the law in your country of residence.\n- type: business\n  text: If you are a business user (i.e. you are using Our Site in the course of business or for commercial purposes)\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: You must not use Our\
  \ site in any way, or for any purpose, that is unlawful or fraudulent\n- summary: Malware and unauthorised access\n  text: You must not attempt to gain unauthorised access to any part of Our Site, the server on which Our Site is\n    stored, or any other server, computer, or database connected to Our Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only Users aged 18 or over may create an Account.\n"
source_yaml_url: https://artifacts.apis.io/little-freddie/eligibility/little-freddie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Little Freddie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Baby Food
- Organic Food
- Food and Beverage
- Consumer Packaged Goods
- Retail
- Parenting
---
