---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: software-as-a-service platform offered by Cents for laundromat owners to track in-store operations
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency use of Cents Assist
    text: Cents Assist is not designed for, and Customer will not use it for or represent that it can handle, emergency communications.
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
name: Cents
provenance_date: '2026-11-09'
provider_name: Cents
provider_slug: cents
slug: cents-eligibility
source_date: '2026-11-09'
source_filename: cents-eligibility.yml
source_heading: Eligibility
source_page: https://www.trycents.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cents\naid: cents\nurl: https://www.trycents.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: software-as-a-service platform offered by Cents for laundromat owners to track in-store operations\nrestricted_uses:\n- summary: No emergency use of Cents Assist\n  text: Cents Assist is not designed for, and Customer will not use it for or represent that it can handle, emergency\n    communications.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cents/eligibility/cents-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Cents's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Software
- Laundry
- Point-of-Sale
- Payments
- Business Management
- Pickup and Delivery
- Software-as-a-Service
- Small Business
---
