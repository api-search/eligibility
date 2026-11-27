---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: They do not apply to purchases made by businesses or for commercial use.
    type: business
  - text: The terms apply to all purchases made on the webshop by consumers for their private use.
    type: individual
  minimum_age:
    text: Any use or access to the Site by anyone under 16 years is strictly prohibited and in violation of this Site Agreement.
    value: '16'
  restricted_uses:
  - summary: Commercial solicitation
    text: using the Site for any commercial solicitation purposes
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
name: Soundboks
provenance_date: '2026-11-10'
provider_name: Soundboks
provider_slug: soundboks
slug: soundboks-eligibility
source_date: '2026-11-10'
source_filename: soundboks-eligibility.yml
source_heading: Eligibility
source_page: https://soundboks.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Soundboks\naid: soundboks\nurl: https://soundboks.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: They do not apply to purchases made by businesses or for commercial use.\n- type: individual\n  text: The terms apply to all purchases made on the webshop by consumers for their private use.\nrestricted_uses:\n- summary: Commercial solicitation\n  text: using the Site for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '16'\n  text: Any use or access to the Site by anyone under 16 years is strictly prohibited and in violation of this Site\n    Agreement.\n"
source_yaml_url: https://artifacts.apis.io/soundboks/eligibility/soundboks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Soundboks's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer Electronics
- Audio
- Bluetooth Speakers
- Hardware
- E-Commerce
- Shopify
- Direct to Consumer
---
