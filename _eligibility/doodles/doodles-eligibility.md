---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are operated by us in the United States.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be 13 years of age or older and reside in the United States or any of its territories to use the Services.
    value: '13'
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services
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
name: Doodles
provenance_date: '2026-11-09'
provider_name: Doodles
provider_slug: doodles
slug: doodles-eligibility
source_date: '2026-11-09'
source_filename: doodles-eligibility.yml
source_heading: Eligibility
source_page: https://www.doodles.app/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doodles\naid: doodles\nurl: https://www.doodles.app/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are operated by us in the United States.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older and reside in the United States or any of its territories to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/doodles/eligibility/doodles-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Doodles's own page on 2026-11-09.
synthetic: false
tags:
- Company
- NFT
- Web3
- Blockchain
- Entertainment
- Media
- Digital Collectibles
- Animation
- Consumer
- Webhook
---
