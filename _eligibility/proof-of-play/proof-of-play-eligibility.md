---
api_specs:
- filename: proof-of-play-public-api-api-openapi.yml
  format: yaml
  label: Proof of Play Public API
  slug: proof-of-play-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proof-of-play/openapi/proof-of-play-public-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    type: individual
  minimum_age:
    text: You must be 18 years of age (or the age of majority in your state), or obtain permission from your parent or legal guardian to purchase Virtual Items
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The provision of Virtual Items is strictly for your personal, non-commercial use in Pirate Nation games.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Pirate Nation may require identity verification before issuing referral rewards that meet or exceed thresholds determined by Pirate Nation in its discretion or where required by law.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Proof of Play
provenance_date: '2026-11-10'
provider_name: Proof of Play
provider_slug: proof-of-play
slug: proof-of-play-eligibility
source_date: '2026-11-10'
source_filename: proof-of-play-eligibility.yml
source_heading: Eligibility
source_page: https://arcade.piratenation.game/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Proof of Play\naid: proof-of-play\nurl: https://arcade.piratenation.game/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: The provision of Virtual Items is strictly for your personal, non-commercial use in Pirate Nation games.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Pirate Nation may require identity verification before\
  \ issuing referral rewards that meet or exceed thresholds\n    determined by Pirate Nation in its discretion or where required by law.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age (or the age of majority in your state), or obtain permission from your parent\n    or legal guardian to purchase Virtual Items\n"
source_yaml_url: https://artifacts.apis.io/proof-of-play/eligibility/proof-of-play-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Proof of Play's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Blockchain
- Web3
- Randomness
- Onchain Infrastructure
- NFT
---
