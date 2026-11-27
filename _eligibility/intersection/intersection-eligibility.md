---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: only for personal or internal business purposes
    type: business
  minimum_age:
    text: that you are at least 13 years old
    value: '13'
  restricted_uses:
  - summary: Unlawful use
    text: use the Services in an unlawful manner
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Intersection
provenance_date: '2026-11-09'
provider_name: Intersection
provider_slug: intersection
slug: intersection-eligibility
source_date: '2026-11-09'
source_filename: intersection-eligibility.yml
source_heading: Eligibility
source_page: https://www.intersection.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intersection\naid: intersection\nurl: https://www.intersection.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: only for personal or internal business purposes\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Services in an unlawful manner\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '13'\n  text: that you are at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/intersection/eligibility/intersection-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Intersection's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Out-of-Home
- Digital Signage
- Media
- Smart Cities
- Transit
- Programmatic
- Agents
- MCP
---
