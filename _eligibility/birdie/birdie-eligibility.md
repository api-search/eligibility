---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This right is granted to the entity named on your Order Form and does not extend to any subsidiary or group company of that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable Use Policy compliance
    text: only use the Services in accordance with this Agreement, the Acceptable Use Policy and the Acceptable Partner Behaviour Policy
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
name: Birdie
provenance_date: '2026-11-09'
provider_name: Birdie
provider_slug: birdie
slug: birdie-eligibility
source_date: '2026-11-09'
source_filename: birdie-eligibility.yml
source_heading: Eligibility
source_page: https://www.birdie.care/terms/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Birdie\naid: birdie\nurl: https://www.birdie.care/terms/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This right is granted to the entity named on your Order Form and does not extend to any subsidiary or group\n    company of that entity.\nrestricted_uses:\n- summary: Acceptable Use Policy compliance\n  text: only use the Services in accordance with this Agreement, the Acceptable Use Policy and the Acceptable Partner\n    Behaviour Policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/birdie/eligibility/birdie-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Birdie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Domiciliary Care
- Care Management
- Rostering
- Social Care
- Health Tech
---
