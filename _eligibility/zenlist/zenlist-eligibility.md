---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The user has relocated to an area in which Zenlist does not service
  entity_types:
  - text: Your membership in the Zenlist service is for your sole, personal use. You may not authorize others to use your membership
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Applicable law compliance
    text: You will use the Zenlist service in a manner consistent with any and all applicable laws and regulations.
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
name: Zenlist
provenance_date: '2026-11-10'
provider_name: Zenlist
provider_slug: zenlist
slug: zenlist-eligibility
source_date: '2026-11-10'
source_filename: zenlist-eligibility.yml
source_heading: Eligibility
source_page: https://zenlist.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenlist\naid: zenlist\nurl: https://zenlist.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The user has relocated to an area in which Zenlist does not service\nentity_types:\n- type: individual\n  text: Your membership in the Zenlist service is for your sole, personal use. You may not authorize others to use\n    your membership\nrestricted_uses:\n- summary: Applicable law compliance\n  text: You will use the Zenlist service in a manner consistent with any and all applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zenlist/eligibility/zenlist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Zenlist's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Home Search
- MLS
- RESO
- Brokerage Software
---
