---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 13 years of age, you may not use the Services.
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you may not use the Services.
    value: '13'
  restricted_uses:
  - summary: Prohibited content and unlawful use
    text: You further agree not to use the Services to communicate any message or material that is harassing, libelous, threatening, obscene, indecent
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
name: Gatheround
provenance_date: '2026-11-09'
provider_name: Gatheround
provider_slug: gatheround
slug: gatheround-eligibility
source_date: '2026-11-09'
source_filename: gatheround-eligibility.yml
source_heading: Eligibility
source_page: https://gatheround.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gatheround\naid: gatheround\nurl: https://gatheround.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 13 years of age, you may not use the Services.\nrestricted_uses:\n- summary: Prohibited content and unlawful use\n  text: You further agree not to use the Services to communicate any message or material that is harassing, libelous,\n    threatening, obscene, indecent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years\
  \ of age, you may not use the Services.\n"
source_yaml_url: https://artifacts.apis.io/gatheround/eligibility/gatheround-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gatheround's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Conferencing
- Online Meetings
- Team Engagement
- Community
- Collaboration
- Employee Engagement
- Remote Work
---
