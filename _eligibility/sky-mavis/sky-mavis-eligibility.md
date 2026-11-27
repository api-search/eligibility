---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site and Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: unlicensed financial activities
    text: to use the Services to carry out or allow the provision of any financial activities that are subject to licensing or registration
  - summary: sanctioned parties
    text: a country, territory, entity, or individual included in any trade embargoes or economic sanctions list
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide additional information and documents in certain circumstances
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sky Mavis
provenance_date: '2026-11-10'
provider_name: Sky Mavis
provider_slug: sky-mavis
slug: sky-mavis-eligibility
source_date: '2026-11-10'
source_filename: sky-mavis-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.skymavis.com/files/skymavis-terms-of-use-09012025.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sky Mavis\naid: sky-mavis\nurl: https://cdn.skymavis.com/files/skymavis-terms-of-use-09012025.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: made between you, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: unlicensed financial activities\n  text: to use the Services to carry out or allow the provision of any financial activities that are subject to\n    licensing or registration\n- summary: sanctioned parties\n  text: a country, territory, entity, or individual included in any trade\
  \ embargoes or economic sanctions list\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to provide additional information and documents in certain circumstances\nminimum_age:\n  value: '18'\n  text: The Site and Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/sky-mavis/eligibility/sky-mavis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sky Mavis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blockchain
- Web3
- Gaming
- NFT
- Wallets
- JSON-RPC
- Cryptocurrency
- Developer Tools
---
