---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The site is managed by Devart from its office within the Czech Republic, a European Union country.
  entity_types:
  - text: The Purchase Order payment method is available only to businesses and other legal entities (corporate customers).
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Each Purchase Order is subject to Devart's prior approval on a case-by-case basis, and Devart may decline a Purchase Order at its sole discretion, without stating a reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Devart
provenance_date: '2026-11-09'
provider_name: Devart
provider_slug: devart
slug: devart-eligibility
source_date: '2026-11-09'
source_filename: devart-eligibility.yml
source_heading: Eligibility
source_page: https://www.devart.com/using-website/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Devart\naid: devart\nurl: https://www.devart.com/using-website/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The site is managed by Devart from its office within the Czech Republic, a European Union country.\nentity_types:\n- type: business\n  text: The Purchase Order payment method is available only to businesses and other legal entities (corporate customers).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Each Purchase Order is subject to Devart's prior approval on a case-by-case basis, and Devart may decline\n\
  \    a Purchase Order at its sole discretion, without stating a reason.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/devart/eligibility/devart-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Devart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Database
- Developer Tools
- Data Connectivity
- Software
---
