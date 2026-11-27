---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are located in a country embargoed by the United States or on the U.S. Treasury Department’s list of Specially Designated Nationals.
  entity_types:
  - text: If you’re accessing our Service on behalf of a legal entity, you agree that you have the authority to bind that entity to these terms
    type: business
  minimum_age:
    text: No one under 13 years of age is allowed to create an Account or use the Service. If you are under 18 years old (or the minimum age of digital consent in your country), you may use the Service only with the approval of your parent or legal guardian
    value: '13'
  restricted_uses:
  - summary: Commercial use of account
    text: use your Account for commercial purposes unless authorized by Playco in writing
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
name: Playco
provenance_date: '2026-11-10'
provider_name: Playco
provider_slug: playco
slug: playco-eligibility
source_date: '2026-11-10'
source_filename: playco-eligibility.yml
source_heading: Eligibility
source_page: https://www.play.co/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Playco\naid: playco\nurl: https://www.play.co/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are located in a country embargoed by the United States or on the U.S. Treasury Department’s list\n    of Specially Designated Nationals.\nentity_types:\n- type: business\n  text: If you’re accessing our Service on behalf of a legal entity, you agree that you have the authority to bind\n    that entity to these terms\nrestricted_uses:\n- summary: Commercial use of account\n  text: use your Account for commercial purposes unless authorized by Playco in writing\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: No one under 13 years of age is allowed to create an Account or use the Service. If you are under 18 years\n    old (or the minimum age of digital consent in your country), you may use the Service only with the approval\n    of your parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/playco/eligibility/playco-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Playco's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Games
- Instant Games
- HTML5
- Game Engine
- Mobile Games
- Social Gaming
- Developer Tools
- Open Source
---
