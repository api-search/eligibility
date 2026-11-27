---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: it is duly incorporated, amalgamated or continued, and existing, under the laws of the jurisdiction of its incorporation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use only at authorized Locations
    text: Retailer will only be permitted to use the Proprietary Offerings or the Equipment, or request any Services, at the Location(s) specified on the applicable Order Form.
  - summary: No use by Affiliates without Order Form
    text: a Retailer entity may not use the Proprietary Offerings at or for any Location operated by any of its Affiliates, unless such use and Location are the subject of a valid Order Form
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
name: Zippin
provenance_date: '2026-11-10'
provider_name: Zippin
provider_slug: zippin
slug: zippin-eligibility
source_date: '2026-11-10'
source_filename: zippin-eligibility.yml
source_heading: Eligibility
source_page: https://www.getzippin.com/en/retailer-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zippin\naid: zippin\nurl: https://www.getzippin.com/en/retailer-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: it is duly incorporated, amalgamated or continued, and existing, under the laws of the jurisdiction of its\n    incorporation\nrestricted_uses:\n- summary: Use only at authorized Locations\n  text: Retailer will only be permitted to use the Proprietary Offerings or the Equipment, or request any Services,\n    at the Location(s) specified on the applicable Order Form.\n- summary: No use by Affiliates\
  \ without Order Form\n  text: a Retailer entity may not use the Proprietary Offerings at or for any Location operated by any of its Affiliates,\n    unless such use and Location are the subject of a valid Order Form\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zippin/eligibility/zippin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Zippin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Retail Technology
- Checkout-Free
- Cashierless
- Computer Vision
- Artificial Intelligence
- Machine Learning
- Point-of-Sale
- Payments
- Loyalty
- Inventory
- Sports Venues
- Airports
- Higher Education
---
