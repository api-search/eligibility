---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to create an account.
    type: individual
  - text: Businesses and creators can buy a sponsor card
    type: business
  minimum_age:
    text: You must be at least 13 years old to create an account.
    value: '13'
  restricted_uses:
  - summary: Sponsor sites with adult content, gambling, scams, malware or unlicensed streaming
    text: Sponsors must own or be authorised to promote the linked site, which must not contain adult content, gambling, scams, malware or unlicensed streaming.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We review every card before and after it goes live and may remove a card that breaks these rules
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AnimeHunt
provenance_date: '2026-11-09'
provider_name: AnimeHunt
provider_slug: animehunt-co
slug: animehunt-co-eligibility
source_date: '2026-11-09'
source_filename: animehunt-co-eligibility.yml
source_heading: Eligibility
source_page: https://animehunt.co/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnimeHunt\naid: animehunt-co\nurl: https://animehunt.co/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to create an account.\n- type: business\n  text: Businesses and creators can buy a sponsor card\nrestricted_uses:\n- summary: Sponsor sites with adult content, gambling, scams, malware or unlicensed streaming\n  text: Sponsors must own or be authorised to promote the linked site, which must not contain adult content, gambling,\n    scams, malware or unlicensed streaming.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: We review every card before and after it goes live and may remove a card that breaks these rules\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/animehunt-co/eligibility/animehunt-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AnimeHunt's own page on 2026-11-09.
synthetic: false
tags:
- Anime
- Manga
- Webtoons
- Discovery
- Tracker
---
