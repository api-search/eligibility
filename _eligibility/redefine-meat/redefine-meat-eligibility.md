---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are not under the age of 16
    value: '16'
  restricted_uses:
  - summary: Under-16 users excluded
    text: you are not under the age of 16
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
name: Redefine Meat
provenance_date: '2026-11-10'
provider_name: Redefine Meat
provider_slug: redefine-meat
slug: redefine-meat-eligibility
source_date: '2026-11-10'
source_filename: redefine-meat-eligibility.yml
source_heading: Eligibility
source_page: https://www.redefinemeat.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Redefine Meat\naid: redefine-meat\nurl: https://www.redefinemeat.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Under-16 users excluded\n  text: you are not under the age of 16\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are not under the age of 16\n"
source_yaml_url: https://artifacts.apis.io/redefine-meat/eligibility/redefine-meat-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Redefine Meat's own page on 2026-11-10.
synthetic: false
tags:
- Food and Beverage
- Alternative Protein
- Plant-Based
- Food Technology
- Manufacturing
- E-Commerce
- WooCommerce
- WordPress
- Retail
- MCP
---
