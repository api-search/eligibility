---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Buyer: the person, firm or company who purchases the Goods and/or Services from the Company.'
    type: individual
  - text: 'Buyer: the person, firm or company who purchases the Goods and/or Services from the Company.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use of website
    text: You must not use our website in any way that causes, or may cause, damage to the website or impairment of the availability or accessibility of the website;
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
name: Warmup (underfloor heating)
provenance_date: '2026-11-10'
provider_name: Warmup (underfloor heating)
provider_slug: warmup
slug: warmup-eligibility
source_date: '2026-11-10'
source_filename: warmup-eligibility.yml
source_heading: Eligibility
source_page: https://www.warmup.co.uk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Warmup (underfloor heating)\naid: warmup\nurl: https://www.warmup.co.uk/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Buyer: the person, firm or company who purchases the Goods and/or Services from the Company.'\n- type: business\n  text: 'Buyer: the person, firm or company who purchases the Goods and/or Services from the Company.'\nrestricted_uses:\n- summary: Acceptable use of website\n  text: You must not use our website in any way that causes, or may cause, damage to the website or impairment of\n    the\
  \ availability or accessibility of the website;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/warmup/eligibility/warmup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Warmup (underfloor heating)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Underfloor Heating
- United Kingdom
- Home Improvement
- HVAC
---
