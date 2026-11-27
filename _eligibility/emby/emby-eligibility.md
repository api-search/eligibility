---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We may also impose restrictions on your ability to establish an account (e.g., age limits, restrict business entities from setting up accounts, limitations on the number of accounts, etc.) in EMBY’s sole discretion.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only for Access Services
    text: You represent and warrant that you will utilize the Access Services solely for non-commercial, private and personal use
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
name: Emby
provenance_date: '2026-11-09'
provider_name: Emby
provider_slug: emby
slug: emby-eligibility
source_date: '2026-11-09'
source_filename: emby-eligibility.yml
source_heading: Eligibility
source_page: https://emby.media/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Emby\naid: emby\nurl: https://emby.media/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We may also impose restrictions on your ability to establish an account (e.g., age limits, restrict business\n    entities from setting up accounts, limitations on the number of accounts, etc.) in EMBY’s sole discretion.\nrestricted_uses:\n- summary: Non-commercial use only for Access Services\n  text: You represent and warrant that you will utilize the Access Services solely for non-commercial, private and\n    personal use\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/emby/eligibility/emby-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Emby's own page on 2026-11-09.
synthetic: false
tags:
- Media Server
- Personal Media
- Streaming
- Video Library
- Music Library
- Live TV
---
