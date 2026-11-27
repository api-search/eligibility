---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: (1) you are at least 18 years old
    type: individual
  minimum_age:
    text: Our Sites are intended for individuals 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: You may not access or use any of our Content or any part of our Sites for commercial purposes, to derive any personal benefit, or to impersonate (or attempt to impersonate) CAVA or any other person.
  - summary: Automated access and scraping
    text: Use any robot, spider, other automatic device, or manual process or means to access the Sites for any purpose, including monitoring, copying, collecting, data mining, extracting, or scraping any of the Content on the Sites.
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
name: CAVA
provenance_date: '2026-11-09'
provider_name: CAVA
provider_slug: cava
slug: cava-eligibility
source_date: '2026-11-09'
source_filename: cava-eligibility.yml
source_heading: Eligibility
source_page: https://cava.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CAVA\naid: cava\nurl: https://cava.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: (1) you are at least 18 years old\nrestricted_uses:\n- summary: Commercial use\n  text: You may not access or use any of our Content or any part of our Sites for commercial purposes, to derive\n    any personal benefit, or to impersonate (or attempt to impersonate) CAVA or any other person.\n- summary: Automated access and scraping\n  text: Use any robot, spider, other automatic device, or manual process or means to access the Sites for any\
  \ purpose,\n    including monitoring, copying, collecting, data mining, extracting, or scraping any of the Content on the Sites.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Sites are intended for individuals 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/cava/eligibility/cava-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CAVA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- Food and Beverage
- Fast Casual
- Hospitality
- Consumer
- Loyalty
- Catering
- Retail
- Mediterranean
---
