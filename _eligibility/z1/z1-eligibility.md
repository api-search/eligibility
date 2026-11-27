---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: There are no geographic restrictions.
  entity_types:
  - text: Mini Party is available to users aged 13 and older.
    type: individual
  minimum_age:
    text: Mini Party is available to users aged 13 and older.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By using mini.party, you represent that you meet this age requirement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Z1
provenance_date: '2026-11-10'
provider_name: Z1
provider_slug: z1
slug: z1-eligibility
source_date: '2026-11-10'
source_filename: z1-eligibility.yml
source_heading: Eligibility
source_page: https://www.mini.party/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Z1\naid: z1\nurl: https://www.mini.party/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: There are no geographic restrictions.\nentity_types:\n- type: individual\n  text: Mini Party is available to users aged 13 and older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By using mini.party, you represent that you meet this age requirement.\nminimum_age:\n  value: '13'\n  text: Mini Party is available to users aged 13 and older.\n"
source_yaml_url: https://artifacts.apis.io/z1/eligibility/z1-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Z1's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Social
- Video Chat
- Party Games
- Mobile
- Entertainment
---
