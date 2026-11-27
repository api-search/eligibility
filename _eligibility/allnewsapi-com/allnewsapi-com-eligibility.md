---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you have the necessary power and authority to enter into this Agreement on the behalf of yourself and/or the entity you represent.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Use the allnewsapi.com API in any manner that violates any laws directly or indirectly.
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
name: allnewsapi-com
provenance_date: '2026-11-09'
provider_name: allnewsapi-com
provider_slug: allnewsapi-com
slug: allnewsapi-com-eligibility
source_date: '2026-11-09'
source_filename: allnewsapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://allnewsapi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: allnewsapi-com\naid: allnewsapi-com\nurl: https://allnewsapi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You represent and warrant that you have the necessary power and authority to enter into this Agreement on\n    the behalf of yourself and/or the entity you represent.\nrestricted_uses:\n- summary: Lawful use only\n  text: Use the allnewsapi.com API in any manner that violates any laws directly or indirectly.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n \
  \ value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/allnewsapi-com/eligibility/allnewsapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from allnewsapi-com's own page on 2026-11-09.
synthetic: false
tags:
- News
- Data
- Media
- Aggregation
- Company
---
