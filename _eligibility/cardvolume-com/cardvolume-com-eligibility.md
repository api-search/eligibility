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
  - summary: No financial or investment reliance
    text: Nothing on this site is financial, investment, or legal advice, and nothing is an offer to buy or sell any card.
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
name: CardVolume
provenance_date: '2026-11-09'
provider_name: CardVolume
provider_slug: cardvolume-com
slug: cardvolume-com-eligibility
source_date: '2026-11-09'
source_filename: cardvolume-com-eligibility.yml
source_heading: Eligibility
source_page: https://cardvolume.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CardVolume\naid: cardvolume-com\nurl: https://cardvolume.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No financial or investment reliance\n  text: Nothing on this site is financial, investment, or legal advice, and nothing is an offer to buy or sell any\n    card.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cardvolume-com/eligibility/cardvolume-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CardVolume's own page on 2026-11-09.
synthetic: false
tags:
- CardVolume
- Trading Cards
- Collectibles
- Market Data
---
