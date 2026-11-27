---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older and authorised to act on behalf of the business you register.
    type: business
  minimum_age:
    text: You must be 18 or older
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose
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
name: BidSkim
provenance_date: '2026-11-09'
provider_name: BidSkim
provider_slug: bidskim
slug: bidskim-eligibility
source_date: '2026-11-09'
source_filename: bidskim-eligibility.yml
source_heading: Eligibility
source_page: https://bidskim.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BidSkim\naid: bidskim\nurl: https://bidskim.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be 18 or older and authorised to act on behalf of the business you register.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older\n"
source_yaml_url: https://artifacts.apis.io/bidskim/eligibility/bidskim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BidSkim's own page on 2026-11-09.
synthetic: false
tags:
- Procurement
- Public Sector
- Tenders
- United Kingdom
- Construction
- Artificial Intelligence
---
