---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: (ii) contains sexually explicit content or pornography
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
name: LiveControl
provenance_date: '2026-11-09'
provider_name: LiveControl
provider_slug: livecontrol
slug: livecontrol-eligibility
source_date: '2026-11-09'
source_filename: livecontrol-eligibility.yml
source_heading: Eligibility
source_page: https://www.livecontrol.io/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiveControl\naid: livecontrol\nurl: https://www.livecontrol.io/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content\n  text: (ii) contains sexually explicit content or pornography\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/livecontrol/eligibility/livecontrol-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from LiveControl's own page on 2026-11-09.
synthetic: false
tags:
- Video
- Streaming
- Remote Production
- Live Events
- Software-as-a-Service
---
