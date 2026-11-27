---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are an individual (i.e., not a corporation)
    type: individual
  minimum_age:
    text: You must be at least 13 years old (or such other minimum age as is applicable in your country and/or state of residence) to create an Account to use the Software.
    value: '13'
  restricted_uses:
  - summary: Commercial activities and sales
    text: involves commercial activities and/or sales without Company
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we may ask you for information about yourself, including your name, photo or other identification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mythical Games
provenance_date: '2026-11-10'
provider_name: Mythical Games
provider_slug: mythical-games
slug: mythical-games-eligibility
source_date: '2026-11-10'
source_filename: mythical-games-eligibility.yml
source_heading: Eligibility
source_page: https://mythicalgames.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mythical Games\naid: mythical-games\nurl: https://mythicalgames.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are an individual (i.e., not a corporation)\nrestricted_uses:\n- summary: Commercial activities and sales\n  text: involves commercial activities and/or sales without Company\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we may ask you for information about yourself, including your name, photo or other identification\nminimum_age:\n  value: '13'\n  text: You must be\
  \ at least 13 years old (or such other minimum age as is applicable in your country and/or state\n    of residence) to create an Account to use the Software.\n"
source_yaml_url: https://artifacts.apis.io/mythical-games/eligibility/mythical-games-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Mythical Games's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Web3
- Blockchain
- Digital Assets
- NFT
- Marketplace
- gRPC
- SDK
- Game Platform
---
