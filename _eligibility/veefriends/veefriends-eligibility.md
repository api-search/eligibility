---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website is offered and available to users who are 13 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Minors
    text: For the purpose of exploiting, harming or attempting to exploit or harm minors in any way by exposing them to inappropriate content, asking for personally identifiable information or otherwise.
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
name: VeeFriends
provenance_date: '2026-11-10'
provider_name: VeeFriends
provider_slug: veefriends
slug: veefriends-eligibility
source_date: '2026-11-10'
source_filename: veefriends-eligibility.yml
source_heading: Eligibility
source_page: https://veefriends.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VeeFriends\naid: veefriends\nurl: https://veefriends.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 13 years of age or older.\nrestricted_uses:\n- summary: Minors\n  text: For the purpose of exploiting, harming or attempting to exploit or harm minors in any way by exposing them\n    to inappropriate content, asking for personally identifiable information or otherwise.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Website is offered and available to users who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/veefriends/eligibility/veefriends-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from VeeFriends's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Collectibles
- NFT
- Trading Cards
- Entertainment
- Comics
- Web3
---
