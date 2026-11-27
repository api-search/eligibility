---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: be physically located in a territory in which participation in the competitions you select on the site is unrestricted by law
  entity_types:
  - text: be a natural person
    type: individual
  minimum_age:
    text: at least non-children (age depending on the country where you reside)
    value: null
  restricted_uses:
  - summary: Individual use only
    text: Accounts for Individual Use Only. You may use the Sites and Services for your personal, non-commercial use only.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: each member will be required to provide proper identification and proof of eligibility prior to receiving a prize or the processing by us of any prize request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OPGG
provenance_date: '2026-11-10'
provider_name: OPGG
provider_slug: opgg
slug: opgg-eligibility
source_date: '2026-11-10'
source_filename: opgg-eligibility.yml
source_heading: Eligibility
source_page: https://op.gg/lol/policies/agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OPGG\naid: opgg\nurl: https://op.gg/lol/policies/agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: be physically located in a territory in which participation in the competitions you select on the site is\n    unrestricted by law\nentity_types:\n- type: individual\n  text: be a natural person\nrestricted_uses:\n- summary: Individual use only\n  text: Accounts for Individual Use Only. You may use the Sites and Services for your personal, non-commercial use\n    only.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: each member will be required to\
  \ provide proper identification and proof of eligibility prior to receiving\n    a prize or the processing by us of any prize request.\nminimum_age:\n  value: null\n  text: at least non-children (age depending on the country where you reside)\n"
source_yaml_url: https://artifacts.apis.io/opgg/eligibility/opgg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from OPGG's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Esports
- Game Data
- Analytics
- League of Legends
- VALORANT
- Statistics
- MCP
---
