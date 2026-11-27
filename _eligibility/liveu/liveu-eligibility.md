---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You affirm that You are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Commercial solicitation via Site
    text: nor to use the communication systems provided by the Site for any commercial solicitation purposes.
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
name: Liveu
provenance_date: '2026-11-09'
provider_name: Liveu
provider_slug: liveu
slug: liveu-eligibility
source_date: '2026-11-09'
source_filename: liveu-eligibility.yml
source_heading: Eligibility
source_page: https://www.liveu.tv/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liveu\naid: liveu\nurl: https://www.liveu.tv/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial solicitation via Site\n  text: nor to use the communication systems provided by the Site for any commercial solicitation purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that You are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/liveu/eligibility/liveu-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Liveu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Live Streaming
- Video Streaming
- Broadcast
- Bonded Cellular
- Video Contribution
- Media and Entertainment
- Sports Production
- Public Safety
- 5G
---
