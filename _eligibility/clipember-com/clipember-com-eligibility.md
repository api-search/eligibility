---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept on behalf of a company, you confirm you may bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Barred users
    text: You may not use ClipEmber if you are barred from doing so under the laws that apply to you, or if a platform you connect has banned you.
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
name: ClipEmber
provenance_date: '2026-11-09'
provider_name: ClipEmber
provider_slug: clipember-com
slug: clipember-com-eligibility
source_date: '2026-11-09'
source_filename: clipember-com-eligibility.yml
source_heading: Eligibility
source_page: https://clipember.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClipEmber\naid: clipember-com\nurl: https://clipember.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept on behalf of a company, you confirm you may bind it.\nrestricted_uses:\n- summary: Barred users\n  text: You may not use ClipEmber if you are barred from doing so under the laws that apply to you, or if a platform\n    you connect has banned you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/clipember-com/eligibility/clipember-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ClipEmber's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Artificial Intelligence
- Video Editing
- Short-Form Video
- Captions
- Social Media
- MCP
---
