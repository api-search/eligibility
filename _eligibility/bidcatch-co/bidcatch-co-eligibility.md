---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your digest is for your business.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No resale, republishing or competing use
    text: you can't resell it, republish it, or feed it into a competing service.
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
name: BidCatch
provenance_date: '2026-11-09'
provider_name: BidCatch
provider_slug: bidcatch-co
slug: bidcatch-co-eligibility
source_date: '2026-11-09'
source_filename: bidcatch-co-eligibility.yml
source_heading: Eligibility
source_page: https://bidcatch.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BidCatch\naid: bidcatch-co\nurl: https://bidcatch.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Your digest is for your business.\nrestricted_uses:\n- summary: No resale, republishing or competing use\n  text: you can't resell it, republish it, or feed it into a competing service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bidcatch-co/eligibility/bidcatch-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BidCatch's own page on 2026-11-09.
synthetic: false
tags:
- Government
- Procurement
- Bids
- EmailDigest
---
