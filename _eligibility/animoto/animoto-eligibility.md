---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we make no representation that the Services are appropriate or available for use in locations outside the United States
  entity_types:
  - text: You must be 13 years of age or older to be a User of the Services.
    type: individual
  - text: you and your school, college, university, or other educational institution (" School ")
    type: other
  minimum_age:
    text: You must be 13 years of age or older to be a User of the Services.
    value: '13'
  restricted_uses:
  - summary: Educational videos non-commercial only
    text: Animoto Videos created for educational or instructional use with students may only be used for personal, non-commercial purposes.
  - summary: Licensed Images restrictions
    text: 'Licensed Images may not be used: on a stand-alone basis with no other content'
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
name: Animoto
provenance_date: '2026-11-09'
provider_name: Animoto
provider_slug: animoto
slug: animoto-eligibility
source_date: '2026-11-09'
source_filename: animoto-eligibility.yml
source_heading: Eligibility
source_page: https://animoto.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Animoto\naid: animoto\nurl: https://animoto.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: we make no representation that the Services are appropriate or available for use in locations outside the\n    United States\nentity_types:\n- type: individual\n  text: You must be 13 years of age or older to be a User of the Services.\n- type: other\n  text: you and your school, college, university, or other educational institution (\" School \")\nrestricted_uses:\n- summary: Educational videos non-commercial only\n  text: Animoto Videos created for educational\
  \ or instructional use with students may only be used for personal,\n    non-commercial purposes.\n- summary: Licensed Images restrictions\n  text: 'Licensed Images may not be used: on a stand-alone basis with no other content'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older to be a User of the Services.\n"
source_yaml_url: https://artifacts.apis.io/animoto/eligibility/animoto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Animoto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Video
- Video Creation
- Video Editing
- Slideshow
- Marketing
- Social Media
- Content Creation
- Software-as-a-Service
---
