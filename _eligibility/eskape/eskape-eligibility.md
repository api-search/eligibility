---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - GB
    served: []
    text: Nor may a business established in the United Kingdom (England, Scotland, Wales or Northern Ireland).
  entity_types:
  - text: independent software developers, experts and IT specialists who evaluate, test and integrate software in the course of their professional activity.
    type: developer
  - text: 'Access is permitted only to: licensed betting operators; business-to-business platforms that provide their systems to licensed operators'
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No consumers or bettors
    text: The Service is not offered to consumers, to members of the public acting outside that professional sphere, or to persons who intend to use the Output to place bets of their own.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ESKape Sportsbook Feed
provenance_date: '2026-11-09'
provider_name: ESKape Sportsbook Feed
provider_slug: eskape
slug: eskape-eligibility
source_date: '2026-11-09'
source_filename: eskape-eligibility.yml
source_heading: Eligibility
source_page: https://eskape.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ESKape Sportsbook Feed\naid: eskape\nurl: https://eskape.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - GB\n  text: Nor may a business established in the United Kingdom (England, Scotland, Wales or Northern Ireland).\nentity_types:\n- type: developer\n  text: independent software developers, experts and IT specialists who evaluate, test and integrate software in\n    the course of their professional activity.\n- type: other\n  text: 'Access is permitted only to: licensed betting operators; business-to-business platforms that provide their\n    systems to licensed operators'\n\
  restricted_uses:\n- summary: No consumers or bettors\n  text: The Service is not offered to consumers, to members of the public acting outside that professional sphere,\n    or to persons who intend to use the Output to place bets of their own.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eskape/eligibility/eskape-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ESKape Sportsbook Feed's own page on 2026-11-09.
synthetic: false
tags:
- Sportsbook
- Odds API
- B2B
- Football
- Betting
---
