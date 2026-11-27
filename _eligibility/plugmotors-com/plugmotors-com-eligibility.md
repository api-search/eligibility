---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This subsection applies to consumers and other users who purchase vehicles through Plug's retail dealership channels ("Retail Buyers").
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal use in wholesale
    text: Vehicles purchased through the wholesale marketplace are intended solely for resale or other legitimate business purposes; purchases for personal consumer use through the wholesale marketplace are not permitted.
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
name: Plug
provenance_date: '2026-11-10'
provider_name: Plug
provider_slug: plugmotors-com
slug: plugmotors-com-eligibility
source_date: '2026-11-10'
source_filename: plugmotors-com-eligibility.yml
source_heading: Eligibility
source_page: https://plugmotors.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plug\naid: plugmotors-com\nurl: https://plugmotors.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This subsection applies to consumers and other users who purchase vehicles through Plug's retail dealership\n    channels (\"Retail Buyers\").\nrestricted_uses:\n- summary: No personal use in wholesale\n  text: Vehicles purchased through the wholesale marketplace are intended solely for resale or other legitimate\n    business purposes; purchases for personal consumer use through the wholesale marketplace are not permitted.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plugmotors-com/eligibility/plugmotors-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Plug's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Electric Vehicles
- Marketplace
- Fintech
- Automotive
---
