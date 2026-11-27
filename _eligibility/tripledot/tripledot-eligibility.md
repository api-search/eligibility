---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not allowed to receive products, including services or software, from the UK, for example if you are located in a country embargoed by the;
  minimum_age:
    text: You are under 13 years of age, in which case you must not create an Account, use any part of the Service except games with an age screen after accurately identifying your age
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: solely for your own non-commercial entertainment purposes
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
name: Tripledot
provenance_date: '2026-11-10'
provider_name: Tripledot
provider_slug: tripledot
slug: tripledot-eligibility
source_date: '2026-11-10'
source_filename: tripledot-eligibility.yml
source_heading: Eligibility
source_page: https://www.tripledotstudios.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tripledot\naid: tripledot\nurl: https://www.tripledotstudios.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not allowed to receive products, including services or software, from the UK, for example if you\n    are located in a country embargoed by the;\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: solely for your own non-commercial entertainment purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are under 13 years of age, in which case you must not\
  \ create an Account, use any part of the Service\n    except games with an age screen after accurately identifying your age\n"
source_yaml_url: https://artifacts.apis.io/tripledot/eligibility/tripledot-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tripledot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Mobile Games
- Casual Games
- Games Publisher
- Entertainment
- United Kingdom
---
