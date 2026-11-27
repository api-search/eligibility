---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: 'Country: Canada United States'
  minimum_age:
    text: You must be the age of majority in the jurisdiction of your residence to use our Services.
    value: age of majority
  restricted_uses:
  - summary: Personal use only
    text: You may not resell, lease or provide them in any other way to anyone else.
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
name: checkout51
provenance_date: '2026-11-09'
provider_name: checkout51
provider_slug: checkout51
slug: checkout51-eligibility
source_date: '2026-11-09'
source_filename: checkout51-eligibility.yml
source_heading: Eligibility
source_page: https://www.checkout51.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: checkout51\naid: checkout51\nurl: https://www.checkout51.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: 'Country: Canada United States'\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: You may not resell, lease or provide them in any other way to anyone else.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be the age of majority in the jurisdiction of your residence to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/checkout51/eligibility/checkout51-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from checkout51's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cashback
- Rewards
- Grocery
- Retail
- Loyalty
- Consumer App
- Receipts
---
