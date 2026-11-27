---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Website, you affirm that you are at least 16 years old or have obtained parental/guardian consent to use the Website.
    type: individual
  minimum_age:
    text: you affirm that you are at least 16 years old or have obtained parental/guardian consent to use the Website.
    value: '16'
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
name: Onibi
provenance_date: '2026-11-10'
provider_name: Onibi
provider_slug: onibi
slug: onibi-eligibility
source_date: '2026-11-10'
source_filename: onibi-eligibility.yml
source_heading: Eligibility
source_page: https://www.tomoendlessblue.com/en/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onibi\naid: onibi\nurl: https://www.tomoendlessblue.com/en/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Website, you affirm that you are at least 16 years old or have obtained parental/guardian consent\n    to use the Website.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you affirm that you are at least 16 years old or have obtained parental/guardian consent to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/onibi/eligibility/onibi-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Onibi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video Games
- Game Development
- Game Studio
- Sandbox MMO
- User Generated Content
- Procedural Generation
- Entertainment
- Consumer Software
---
