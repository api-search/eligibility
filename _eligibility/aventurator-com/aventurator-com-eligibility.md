---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Under-14s cannot contract directly; a parent or guardian books on their behalf.
    type: individual
  minimum_age:
    text: Under-14s cannot contract directly; a parent or guardian books on their behalf. Some activities require a higher minimum age, stated in the listing.
    value: '14'
  restricted_uses:
  - summary: User obligations
    text: Accurate data, punctual arrival, follow safety instructions. Declare medical conditions, meet the minimum age stated in each listing.
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
name: Aventurator
provenance_date: '2026-11-09'
provider_name: Aventurator
provider_slug: aventurator-com
slug: aventurator-com-eligibility
source_date: '2026-11-09'
source_filename: aventurator-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.aventurator.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aventurator\naid: aventurator-com\nurl: https://www.aventurator.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Under-14s cannot contract directly; a parent or guardian books on their behalf.\nrestricted_uses:\n- summary: User obligations\n  text: Accurate data, punctual arrival, follow safety instructions. Declare medical conditions, meet the minimum\n    age stated in each listing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: Under-14s cannot contract\
  \ directly; a parent or guardian books on their behalf. Some activities require\n    a higher minimum age, stated in the listing.\n"
source_yaml_url: https://artifacts.apis.io/aventurator-com/eligibility/aventurator-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aventurator's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Adventure
- Navigation
- Mobile App
- Canary Islands
---
