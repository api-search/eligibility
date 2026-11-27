---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representation that the Website is appropriate or available in other locations other than where it is operated by Company.
  entity_types:
  - text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) are not permitted to register for the Website or use the Company Services.
    type: individual
  minimum_age:
    text: generally under the age of 18
    value: '18'
  restricted_uses:
  - summary: Commercial use restricted
    text: The Website may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by Company.
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
name: Automotus
provenance_date: '2026-11-09'
provider_name: Automotus
provider_slug: automotus
slug: automotus-eligibility
source_date: '2026-11-09'
source_filename: automotus-eligibility.yml
source_heading: Eligibility
source_page: https://www.automotus.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Automotus\naid: automotus\nurl: https://www.automotus.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representation that the Website is appropriate or available in other locations other than\n    where it is operated by Company.\nentity_types:\n- type: individual\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) are not\n    permitted to register for the Website or use the Company Services.\nrestricted_uses:\n- summary: Commercial use restricted\n  text: The Website may not be used in connection\
  \ with any commercial endeavors except those that are specifically\n    endorsed or approved by Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: generally under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/automotus/eligibility/automotus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Automotus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Smart Cities
- Urban Mobility
- Curb Management
- Computer Vision
- Transportation
- Parking
- Enforcement
---
