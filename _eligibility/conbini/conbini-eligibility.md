---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By placing an order, you warrant that you are over 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: By placing an order, you represent that the products ordered will be used only in a lawful manner.
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
name: Conbini
provenance_date: '2026-11-09'
provider_name: Conbini
provider_slug: conbini
slug: conbini-eligibility
source_date: '2026-11-09'
source_filename: conbini-eligibility.yml
source_heading: Eligibility
source_page: https://conbini.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conbini\naid: conbini\nurl: https://conbini.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: By placing an order, you represent that the products ordered will be used only in a lawful manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By placing an order, you warrant that you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/conbini/eligibility/conbini-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Conbini's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Japan
- Snacks
---
