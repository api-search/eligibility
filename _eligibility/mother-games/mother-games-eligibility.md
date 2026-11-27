---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: those persons who choose to access the Services from outside of the U.S. do so on their own initiative and are solely responsible for compliance with local laws and U.S. export laws
  entity_types:
  - text: the individual agreeing to these Legal Terms ("you")
    type: individual
  minimum_age:
    text: The Services are intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Use violating applicable law
    text: Any use of the Services in violation of applicable law is prohibited.
  - summary: Commercial endeavors
    text: The Services may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
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
name: Mother Games
provenance_date: '2026-11-10'
provider_name: Mother Games
provider_slug: mother-games
slug: mother-games-eligibility
source_date: '2026-11-10'
source_filename: mother-games-eligibility.yml
source_heading: Eligibility
source_page: https://www.mothergames.com/policy/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mother Games\naid: mother-games\nurl: https://www.mothergames.com/policy/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: those persons who choose to access the Services from outside of the U.S. do so on their own initiative and\n    are solely responsible for compliance with local laws and U.S. export laws\nentity_types:\n- type: individual\n  text: the individual agreeing to these Legal Terms (\"you\")\nrestricted_uses:\n- summary: Use violating applicable law\n  text: Any use of the Services in violation of applicable law is prohibited.\n- summary: Commercial endeavors\n\
  \  text: The Services may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/mother-games/eligibility/mother-games-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Mother Games's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Mobile Games
- Social Games
- Entertainment
---
