---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: (C) you are 16 years of age or older
    value: '16'
  restricted_uses:
  - summary: Virtual Goods resale
    text: You may not sell or transfer, or attempt to sell or transfer, Virtual Goods, except as specifically permitted as part of the Service.
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
name: Wave
provenance_date: '2026-11-10'
provider_name: Wave
provider_slug: wave
slug: wave-eligibility
source_date: '2026-11-10'
source_filename: wave-eligibility.yml
source_heading: Eligibility
source_page: https://wavexr.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wave\naid: wave\nurl: https://wavexr.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Virtual Goods resale\n  text: You may not sell or transfer, or attempt to sell or transfer, Virtual Goods, except as specifically permitted\n    as part of the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: (C) you are 16 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/wave/eligibility/wave-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Wave's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Entertainment
- Virtual Reality
- Augmented Reality
- Metaverse
- Music
- Live Events
- Avatars
- Extended Reality
- Media
---
