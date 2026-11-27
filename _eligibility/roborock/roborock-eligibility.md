---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: minors should read this Agreement accompanied by legal guardian
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content and behavior
    text: 'You shall not use the Site or Roborock Services to engage in any behavior or activity stated below:'
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
name: Roborock
provenance_date: '2026-11-10'
provider_name: Roborock
provider_slug: roborock
slug: roborock-eligibility
source_date: '2026-11-10'
source_filename: roborock-eligibility.yml
source_heading: Eligibility
source_page: https://us.roborock.com/pages/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roborock\naid: roborock\nurl: https://us.roborock.com/pages/user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: minors should read this Agreement accompanied by legal guardian\nrestricted_uses:\n- summary: Prohibited content and behavior\n  text: 'You shall not use the Site or Roborock Services to engage in any behavior or activity stated below:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/roborock/eligibility/roborock-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Roborock's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Robot Vacuum
- Consumer IoT
- Smart Home
- Home Appliances
---
