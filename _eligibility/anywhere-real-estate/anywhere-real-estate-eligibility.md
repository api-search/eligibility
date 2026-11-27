---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs or API Data... if (b) you are a person barred from using or receiving the APIs or API Data under the applicable laws of the United States or other countries including the country in which you reside
  entity_types:
  - text: IF YOU ARE AN INDIVIDUAL CONSUMER, YOU ARE NOT PERMITTED TO ACCESS OR USE APIs OR API DATA.
    type: individual
  - text: the APIs and API Data are solely intended for use by developers requiring access to Anywhere APIs
    type: developer
  - text: Unless prohibited by applicable law, if you are a business, you will defend and indemnify Anywhere
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal data of EEA/UK/Swiss persons
    text: Use Anywhere APIs to leverage, store, or process Anywhere data for (a) any information relating, directly or indirectly, to an identified or identifiable natural person located in the European Economic Area (“EEA”), Switzerland and/or the United Kingdom
  - summary: HIPAA protected health information
    text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Anywhere unless you have received prior written consent
  - summary: High-risk activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: In order to access APIs, you are required to register and be approved for a developer account through the API Portal.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Anywhere Real Estate
provenance_date: '2026-11-09'
provider_name: Anywhere Real Estate
provider_slug: anywhere-real-estate
slug: anywhere-real-estate-eligibility
source_date: '2026-11-09'
source_filename: anywhere-real-estate-eligibility.yml
source_heading: Eligibility
source_page: https://developers.anywhere.re/terms-use-api-license-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anywhere Real Estate\naid: anywhere-real-estate\nurl: https://developers.anywhere.re/terms-use-api-license-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs or API Data... if (b) you are a person barred from using or receiving the APIs\n    or API Data under the applicable laws of the United States or other countries including the country in which\n    you reside\nentity_types:\n- type: individual\n  text: IF YOU ARE AN INDIVIDUAL CONSUMER, YOU ARE NOT PERMITTED TO ACCESS OR USE APIs OR API DATA.\n- type: developer\n  text: the APIs and API Data are\
  \ solely intended for use by developers requiring access to Anywhere APIs\n- type: business\n  text: Unless prohibited by applicable law, if you are a business, you will defend and indemnify Anywhere\nrestricted_uses:\n- summary: Personal data of EEA/UK/Swiss persons\n  text: Use Anywhere APIs to leverage, store, or process Anywhere data for (a) any information relating, directly\n    or indirectly, to an identified or identifiable natural person located in the European Economic Area (“EEA”),\n    Switzerland and/or the United Kingdom\n- summary: HIPAA protected health information\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Anywhere unless you have received prior written consent\n- summary: High-risk activities\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: In order to access APIs, you are required to register and be approved for a developer account through the\n    API Portal.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anywhere-real-estate/eligibility/anywhere-real-estate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 8 quoted statements, read from Anywhere Real Estate's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- United States
- Property Listings
- MLS
- RESO
- Brokerage
- Franchising
- PropTech
- Title
- Escrow
- Relocation
- Leads
- Transaction
- Residential
---
