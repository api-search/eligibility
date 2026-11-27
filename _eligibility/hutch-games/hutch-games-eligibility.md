---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'you are not located in a country that is: (i) subject to a US Government embargo or has been designated by the US Government as a ''terrorist supporting'' country'
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Chat facility age limit
    text: you are at least 18 years of age
  - summary: Virtual Item purchase jurisdictions
    text: Virtual Items may only be purchased and used by players in jurisdictions where such activities are permitted under applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: verify your information by requesting certain documents and refuse your requests to play Games if we believe there is reason to do so
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hutch Games
provenance_date: '2026-11-09'
provider_name: Hutch Games
provider_slug: hutch-games
slug: hutch-games-eligibility
source_date: '2026-11-09'
source_filename: hutch-games-eligibility.yml
source_heading: Eligibility
source_page: https://www.hutch.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hutch Games\naid: hutch-games\nurl: https://www.hutch.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'you are not located in a country that is: (i) subject to a US Government embargo or has been designated\n    by the US Government as a ''terrorist supporting'' country'\nentity_types: []\nrestricted_uses:\n- summary: Chat facility age limit\n  text: you are at least 18 years of age\n- summary: Virtual Item purchase jurisdictions\n  text: Virtual Items may only be purchased and used by players in jurisdictions where such activities are permitted\n    under applicable\
  \ law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: verify your information by requesting certain documents and refuse your requests to play Games if we believe\n    there is reason to do so\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/hutch-games/eligibility/hutch-games-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Hutch Games's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Entertainment
- Gaming
- Mobile Games
- Game Development
- Racing Games
- Free-to-Play
- Mobile
- Console
- United Kingdom
---
