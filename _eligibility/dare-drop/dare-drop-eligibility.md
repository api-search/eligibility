---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Dare Drop is for your personal, non-commercial use
    type: individual
  minimum_age:
    text: To use Dare Drop, you need to be 13 years old or older.
    value: '13'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right, in our sole discretion, to accept or reject your campaign and the use of our Site and/or Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dare Drop
provenance_date: '2026-11-09'
provider_name: Dare Drop
provider_slug: dare-drop
slug: dare-drop-eligibility
source_date: '2026-11-09'
source_filename: dare-drop-eligibility.yml
source_heading: Eligibility
source_page: https://daredrop.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dare Drop\naid: dare-drop\nurl: https://daredrop.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Dare Drop is for your personal, non-commercial use\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right, in our sole discretion, to accept or reject your campaign and the use of our Site\n    and/or Service.\nminimum_age:\n  value: '13'\n  text: To use Dare Drop, you need to be 13 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/dare-drop/eligibility/dare-drop-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Dare Drop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Influencer Marketing
- Content Creators
- Streaming
- Twitch
- YouTube
- TikTok
- Marketing
---
