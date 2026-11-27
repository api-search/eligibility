---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: the materials in the site are presented solely for the purpose of promoting products and providing support to customers in the United States and Canada.
  entity_types:
  - text: The Site and its content are for your personal, non-commercial use.
    type: individual
  minimum_age:
    text: The Site is not directed at children under the age of 13 (thirteen).
    value: '13'
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: You may not use the Site for any purpose that is unlawful or not authorized by these Terms.
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
name: Epson
provenance_date: '2026-11-09'
provider_name: Epson
provider_slug: epson
slug: epson-eligibility
source_date: '2026-11-09'
source_filename: epson-eligibility.yml
source_heading: Eligibility
source_page: https://epson.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Epson\naid: epson\nurl: https://epson.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: the materials in the site are presented solely for the purpose of promoting products and providing support\n    to customers in the United States and Canada.\nentity_types:\n- type: individual\n  text: The Site and its content are for your personal, non-commercial use.\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: You may not use the Site for any purpose that is unlawful or not authorized by these Terms.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is not directed at children under the age of 13 (thirteen).\n"
source_yaml_url: https://artifacts.apis.io/epson/eligibility/epson-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Epson's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Printing
- Imaging
- Automation
- Hardware
- Consumer
---
