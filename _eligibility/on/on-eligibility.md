---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you reside outside of above listed countries, the GTC govern the rights and obligations between On AG and the Customer.
  minimum_age:
    text: Everyone who is of legal age in their place of residence and at least 18 years old is eligible to participate in the Event, unless otherwise stated in the Special Terms.
    value: '18'
  restricted_uses:
  - summary: Cyclon personal use only
    text: You only have the right to exclusively use the Products for your personal use.
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
name: 'On'
provenance_date: '2026-11-10'
provider_name: 'On'
provider_slug: 'on'
slug: on-eligibility
source_date: '2026-11-10'
source_filename: on-eligibility.yml
source_heading: Eligibility
source_page: https://www.on.com/en-us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 'On'\naid: 'on'\nurl: https://www.on.com/en-us/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you reside outside of above listed countries, the GTC govern the rights and obligations between On AG\n    and the Customer.\nentity_types: []\nrestricted_uses:\n- summary: Cyclon personal use only\n  text: You only have the right to exclusively use the Products for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Everyone who is of legal age in their place\
  \ of residence and at least 18 years old is eligible to participate\n    in the Event, unless otherwise stated in the Special Terms.\n"
source_yaml_url: https://artifacts.apis.io/on/eligibility/on-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from On's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Footwear
- Running
- Apparel
- Athletic
- Sportswear
- Retail
---
