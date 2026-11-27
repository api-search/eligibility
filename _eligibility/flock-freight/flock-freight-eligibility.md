---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you must be at least 18 years old, or the age of majority in your state, whichever is older
    value: '18'
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
name: Flock Freight
provenance_date: '2026-11-09'
provider_name: Flock Freight
provider_slug: flock-freight
slug: flock-freight-eligibility
source_date: '2026-11-09'
source_filename: flock-freight-eligibility.yml
source_heading: Eligibility
source_page: https://www.flockfreight.com/resources/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flock Freight\naid: flock-freight\nurl: https://www.flockfreight.com/resources/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old, or the age of majority in your state, whichever is older\n"
source_yaml_url: https://artifacts.apis.io/flock-freight/eligibility/flock-freight-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Flock Freight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Freight
- Logistics
- Shipping
- Transportation
- Supply Chain
- Freight Brokerage
---
