---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The GTC apply only to entrepreneurs (Section 14 BGB), legal entities under public law or special funds under public law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial resale
    text: ROBCO reserves the right to refuse Offers to conclude contracts if they appear to be for commercial resale.
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
name: Robco
provenance_date: '2026-11-10'
provider_name: Robco
provider_slug: robco
slug: robco-eligibility
source_date: '2026-11-10'
source_filename: robco-eligibility.yml
source_heading: Eligibility
source_page: https://www.rob.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Robco\naid: robco\nurl: https://www.rob.co/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The GTC apply only to entrepreneurs (Section 14 BGB), legal entities under public law or special funds under\n    public law.\nrestricted_uses:\n- summary: Commercial resale\n  text: ROBCO reserves the right to refuse Offers to conclude contracts if they appear to be for commercial resale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/robco/eligibility/robco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Robco's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Industrial Automation
- Robotics as a Service
- Manufacturing
- No-Code
- Computer Vision
- Physical AI
- Automation
---
