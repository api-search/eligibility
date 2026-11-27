---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are over the age of 18, have the right and authority to enter into this Agreement
    type: individual
  - text: provide true, accurate, current and complete information about yourself and your business
    type: business
  minimum_age:
    text: You represent that you are over the age of 18
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: You are prohibited from using the Services to post or send any unlawful, threatening, defamatory, libelous, obscene, pornographic or profane material
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
name: Lish
provenance_date: '2026-11-09'
provider_name: Lish
provider_slug: lish
slug: lish-eligibility
source_date: '2026-11-09'
source_filename: lish-eligibility.yml
source_heading: Eligibility
source_page: https://www.lishfood.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lish\naid: lish\nurl: https://www.lishfood.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are over the age of 18, have the right and authority to enter into this Agreement\n- type: business\n  text: provide true, accurate, current and complete information about yourself and your business\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: You are prohibited from using the Services to post or send any unlawful, threatening, defamatory, libelous,\n    obscene, pornographic or profane\
  \ material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/lish/eligibility/lish-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lish's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Catering
- Food and Beverage
- Food Delivery
- Workplace
- Corporate Services
- Content
---
