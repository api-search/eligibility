---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Any use or access to the Service by anyone under 13 (or under the age of digital consent in their respective country) is strictly prohibited
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You may use our platform only for lawful purposes.
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
name: Kick (kick.com)
provenance_date: '2026-11-09'
provider_name: Kick (kick.com)
provider_slug: kick-com
slug: kick-com-eligibility
source_date: '2026-11-09'
source_filename: kick-com-eligibility.yml
source_heading: Eligibility
source_page: https://kick.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kick (kick.com)\naid: kick-com\nurl: https://kick.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You may use our platform only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 (or under the age of digital consent in their respective\n    country) is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/kick-com/eligibility/kick-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Kick (kick.com)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Streaming
- Live
- Video
- Community
- Platform
---
