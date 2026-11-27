---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Website on behalf of a company or other entity, you represent and warrant that you are authorized to bind such entity to the provisions hereof.
    type: business
  minimum_age:
    text: you warrant that you are at least 13 years old
    value: '13'
  restricted_uses:
  - summary: No data mining or robots
    text: You may not use any data mining, robots, or similar data gathering tools or otherwise exploit your access to the Services
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
name: Zefr
provenance_date: '2026-11-10'
provider_name: Zefr
provider_slug: zefr
slug: zefr-eligibility
source_date: '2026-11-10'
source_filename: zefr-eligibility.yml
source_heading: Eligibility
source_page: https://zefr.com/terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zefr\naid: zefr\nurl: https://zefr.com/terms-of-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Website on behalf of a company or other entity, you represent and warrant that\n    you are authorized to bind such entity to the provisions hereof.\nrestricted_uses:\n- summary: No data mining or robots\n  text: You may not use any data mining, robots, or similar data gathering tools or otherwise exploit your access\n    to the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: you warrant that you are at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/zefr/eligibility/zefr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Zefr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AdTech
- Brand Safety
- Brand Suitability
- Content Intelligence
- Content Moderation
- Video
- Social Media
- Advertising
- Media Measurement
- Machine Learning
---
