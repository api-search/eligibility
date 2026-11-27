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
  - summary: Illegal activities and IP infringement
    text: (2) engages in illegal activities, (3) engages in, induces, or contributes to any intellectual property infringement
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
name: RESO (Real Estate Standards Organization)
provenance_date: '2026-11-10'
provider_name: RESO (Real Estate Standards Organization)
provider_slug: reso
slug: reso-eligibility
source_date: '2026-11-10'
source_filename: reso-eligibility.yml
source_heading: Eligibility
source_page: https://www.reso.org/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RESO (Real Estate Standards Organization)\naid: reso\nurl: https://www.reso.org/eula/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal activities and IP infringement\n  text: (2) engages in illegal activities, (3) engages in, induces, or contributes to any intellectual property\n    infringement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reso/eligibility/reso-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from RESO (Real Estate Standards Organization)'s own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- United States
- RESO
- MLS
- Property Listings
- Data Standards
- OData
- Industry Body
- IDX
- PropTech
---
