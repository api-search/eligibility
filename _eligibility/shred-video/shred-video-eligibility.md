---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the App and Service by anyone under the age of 13 is prohibited.
    type: individual
  minimum_age:
    text: Use of the App and Service by anyone under the age of 13 is prohibited.
    value: '13'
  restricted_uses:
  - summary: Non-commercial only
    text: Any use of the App or Service other than for private, non-commercial use is strictly prohibited.
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
name: Shred Video
provenance_date: '2026-11-10'
provider_name: Shred Video
provider_slug: shred-video
slug: shred-video-eligibility
source_date: '2026-11-10'
source_filename: shred-video-eligibility.yml
source_heading: Eligibility
source_page: https://shredvideo.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shred Video\naid: shred-video\nurl: https://shredvideo.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of the App and Service by anyone under the age of 13 is prohibited.\nrestricted_uses:\n- summary: Non-commercial only\n  text: Any use of the App or Service other than for private, non-commercial use is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Use of the App and Service by anyone under the age of 13 is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/shred-video/eligibility/shred-video-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Shred Video's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Adventure Tourism
- Media
- Automation
- Computer Vision
- Content Delivery
---
