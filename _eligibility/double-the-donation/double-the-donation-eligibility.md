---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the client organization (the “ Client ”) executing and delivering any Order
    type: other
  minimum_age:
    text: null
    value: null
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
name: Double the Donation
provenance_date: '2026-11-09'
provider_name: Double the Donation
provider_slug: double-the-donation
slug: double-the-donation-eligibility
source_date: '2026-11-09'
source_filename: double-the-donation-eligibility.yml
source_heading: Eligibility
source_page: https://doublethedonation.com/master-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Double the Donation\naid: double-the-donation\nurl: https://doublethedonation.com/master-terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the client organization (the “ Client ”) executing and delivering any Order\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/double-the-donation/eligibility/double-the-donation-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Double the Donation's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Non-Profit
- Fundraising
- Matching Gifts
- Software-as-a-Service
---
