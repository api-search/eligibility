---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use ShadowBot Gaming.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use ShadowBot Gaming.
    value: '13'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Platform for any unlawful purpose.
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
name: ShadowBot
provenance_date: '2026-11-10'
provider_name: ShadowBot
provider_slug: shadowbot
slug: shadowbot-eligibility
source_date: '2026-11-10'
source_filename: shadowbot-eligibility.yml
source_heading: Eligibility
source_page: https://shadowbot.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShadowBot\naid: shadowbot\nurl: https://shadowbot.tech/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use ShadowBot Gaming.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Platform for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use ShadowBot Gaming.\n"
source_yaml_url: https://artifacts.apis.io/shadowbot/eligibility/shadowbot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ShadowBot's own page on 2026-11-10.
synthetic: false
tags:
- Gaming
- HTML5
- Free
- Browser
---
