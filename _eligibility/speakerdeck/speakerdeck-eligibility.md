---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Speaker Deck is available only to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: Speaker Deck is available only to individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Sexually explicit content
    text: Is sexually explicit or promotes a sexual service;
  - summary: Violating applicable law
    text: Violates any applicable law.
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
name: Speaker Deck
provenance_date: '2026-11-10'
provider_name: Speaker Deck
provider_slug: speakerdeck
slug: speakerdeck-eligibility
source_date: '2026-11-10'
source_filename: speakerdeck-eligibility.yml
source_heading: Eligibility
source_page: https://speakerdeck.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Speaker Deck\naid: speakerdeck\nurl: https://speakerdeck.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Speaker Deck is available only to individuals who are at least 13 years old.\nrestricted_uses:\n- summary: Sexually explicit content\n  text: Is sexually explicit or promotes a sexual service;\n- summary: Violating applicable law\n  text: Violates any applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Speaker Deck is available only to individuals\
  \ who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/speakerdeck/eligibility/speakerdeck-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Speaker Deck's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Presentation
- Sharing
- Slides
- Education
- Developers
---
