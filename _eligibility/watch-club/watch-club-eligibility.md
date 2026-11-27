---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Mobile App, you represent and warrant that you are at least 18 years of age. If you are under the age of 18, you must have parental or guardian consent to use this Mobile App.
    type: individual
  minimum_age:
    text: By using the Mobile App, you represent and warrant that you are at least 18 years of age.
    value: '18'
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
name: Watch Club
provenance_date: '2026-11-10'
provider_name: Watch Club
provider_slug: watch-club
slug: watch-club-eligibility
source_date: '2026-11-10'
source_filename: watch-club-eligibility.yml
source_heading: Eligibility
source_page: https://watchclubtv.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Watch Club\naid: watch-club\nurl: https://watchclubtv.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Mobile App, you represent and warrant that you are at least 18 years of age. If you are under\n    the age of 18, you must have parental or guardian consent to use this Mobile App.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Mobile App, you represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/watch-club/eligibility/watch-club-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Watch Club's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Streaming
- Video
- Entertainment
- Social
- Mobile
- Media
---
