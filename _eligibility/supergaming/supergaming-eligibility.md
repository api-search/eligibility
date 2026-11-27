---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By registering for an Account or otherwise using the Service, you represent that you are age 13 or older.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: 'The following restrictions apply to the use of the Service: You shall not create an Account or access the Service if you are under the age of 13;'
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
name: SuperGaming
provenance_date: '2026-11-10'
provider_name: SuperGaming
provider_slug: supergaming
slug: supergaming-eligibility
source_date: '2026-11-10'
source_filename: supergaming-eligibility.yml
source_heading: Eligibility
source_page: https://www.supergaming.com/tos.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SuperGaming\naid: supergaming\nurl: https://www.supergaming.com/tos.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: 'The following restrictions apply to the use of the Service: You shall not create an Account or access the\n    Service if you are under the age of 13;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By registering for an Account or otherwise using the Service, you represent that you are\
  \ age 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/supergaming/eligibility/supergaming-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from SuperGaming's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Video Games
- Game Development
- Multiplayer
- Live Operations
- Mobile Games
- Emerging Markets
---
