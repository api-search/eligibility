---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU REPRESENT A LEGAL ENTITY, THE LEGAL ENTITY YOU REPRESENT (COLLECTIVELY, “YOU”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk applications
    text: The Solution is not designed, manufactured, or intended for use in hazardous applications which require fail-safe performance, such as nuclear, aviation, navigation, military, life -support or other high risk activities
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
name: Actifio
provenance_date: '2026-11-09'
provider_name: Actifio
provider_slug: actifio
slug: actifio-eligibility
source_date: '2026-11-09'
source_filename: actifio-eligibility.yml
source_heading: Eligibility
source_page: https://www.actifio.com/assets/Clickthrough-EULA-9-23-19.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Actifio\naid: actifio\nurl: https://www.actifio.com/assets/Clickthrough-EULA-9-23-19.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU REPRESENT A LEGAL ENTITY, THE LEGAL ENTITY YOU REPRESENT (COLLECTIVELY, “YOU”)\nrestricted_uses:\n- summary: High-risk applications\n  text: The Solution is not designed, manufactured, or intended for use in hazardous applications which require\n    fail-safe performance, such as nuclear, aviation, navigation, military, life -support or other high risk activities\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/actifio/eligibility/actifio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Actifio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Management
- Backup
- Disaster Recovery
- Copy Data Management
- Business Continuity
- Cloud
- Enterprise Storage
---
