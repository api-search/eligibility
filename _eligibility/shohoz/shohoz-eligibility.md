---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted and prohibited goods
    text: Any passenger carrying illegal, restricted, unsafe, or prohibited goods.
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
name: Shohoz
provenance_date: '2026-11-10'
provider_name: Shohoz
provider_slug: shohoz
slug: shohoz-eligibility
source_date: '2026-11-10'
source_filename: shohoz-eligibility.yml
source_heading: Eligibility
source_page: https://www.shohoz.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shohoz\naid: shohoz\nurl: https://www.shohoz.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Restricted and prohibited goods\n  text: Any passenger carrying illegal, restricted, unsafe, or prohibited goods.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shohoz/eligibility/shohoz-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Shohoz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ticketing
- Ride Hailing
- Mobility
- Travel
- Transportation
- Delivery
- Bangladesh
- Consumer
---
