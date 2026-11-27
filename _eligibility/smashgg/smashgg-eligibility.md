---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only use the Services if you reside in a jurisdiction that permits you to access the Services.
  entity_types:
  - text: the Services are made available to individuals aged 13 or older
    type: individual
  minimum_age:
    text: 'FOR RESIDENTS IN NORTH AMERICA ONLY: Subject to any applicable restrictions and requirements, the Services are made available to individuals aged 13 or older.'
    value: '13'
  restricted_uses:
  - summary: Lawful use only
    text: By accessing or using the Services, you represent and warrant that your activities are lawful in every jurisdiction where you access or use the Services.
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
name: Smashgg
provenance_date: '2026-11-10'
provider_name: Smashgg
provider_slug: smashgg
slug: smashgg-eligibility
source_date: '2026-11-10'
source_filename: smashgg-eligibility.yml
source_heading: Eligibility
source_page: https://www.start.gg/about/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smashgg\naid: smashgg\nurl: https://www.start.gg/about/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may only use the Services if you reside in a jurisdiction that permits you to access the Services.\nentity_types:\n- type: individual\n  text: the Services are made available to individuals aged 13 or older\nrestricted_uses:\n- summary: Lawful use only\n  text: By accessing or using the Services, you represent and warrant that your activities are lawful in every jurisdiction\n    where you access or use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: 'FOR RESIDENTS IN NORTH AMERICA ONLY: Subject to any applicable restrictions and requirements, the Services\n    are made available to individuals aged 13 or older.'\n"
source_yaml_url: https://artifacts.apis.io/smashgg/eligibility/smashgg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Smashgg's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Esports
- Gaming
- Tournaments
- GraphQL
- Event
- Developer API
---
