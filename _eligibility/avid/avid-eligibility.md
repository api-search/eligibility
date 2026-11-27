---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a purchaser of an Avid product to which the API Documentation relates, you may use the API Documentation to integrate into your proprietary application for your internal use (“Limited Purpose”).
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: The API documentation on this site (“API Documentation”) is provided for your own non-commercial, personal use.
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
name: Avid
provenance_date: '2026-11-09'
provider_name: Avid
provider_slug: avid
slug: avid-eligibility
source_date: '2026-11-09'
source_filename: avid-eligibility.yml
source_heading: Eligibility
source_page: https://developer.avid.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avid\naid: avid\nurl: https://developer.avid.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a purchaser of an Avid product to which the API Documentation relates, you may use the API Documentation\n    to integrate into your proprietary application for your internal use (“Limited Purpose”).\nrestricted_uses:\n- summary: Non-commercial use only\n  text: The API documentation on this site (“API Documentation”) is provided for your own non-commercial, personal\n    use.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avid/eligibility/avid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Avid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Software
- Audio
- Video
---
