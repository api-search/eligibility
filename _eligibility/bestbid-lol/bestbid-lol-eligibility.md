---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally able to make the purchase.
    type: individual
  - text: If acting for a business or another person, you must have authority to do so and to promote the submitted destination.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to make the purchase.
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
name: BestBid.lol
provenance_date: '2026-11-09'
provider_name: BestBid.lol
provider_slug: bestbid-lol
slug: bestbid-lol-eligibility
source_date: '2026-11-09'
source_filename: bestbid-lol-eligibility.yml
source_heading: Eligibility
source_page: https://bestbid.lol/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BestBid.lol\naid: bestbid-lol\nurl: https://bestbid.lol/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to make the purchase.\n- type: business\n  text: If acting for a business or another person, you must have authority to do so and to promote the submitted\n    destination.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to make the purchase.\n"
source_yaml_url: https://artifacts.apis.io/bestbid-lol/eligibility/bestbid-lol-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from BestBid.lol's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Marketplace
- Rankings
- Transparency
- Community
---
