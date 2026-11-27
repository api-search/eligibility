---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old and authorized to bind the organization you represent.
    value: '18'
  restricted_uses:
  - summary: Competing product
    text: use the Services to build a competing product
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
name: Mentlio
provenance_date: '2026-11-10'
provider_name: Mentlio
provider_slug: mentlio
slug: mentlio-eligibility
source_date: '2026-11-10'
source_filename: mentlio-eligibility.yml
source_heading: Eligibility
source_page: https://www.mentlio.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mentlio\naid: mentlio\nurl: https://www.mentlio.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competing product\n  text: use the Services to build a competing product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and authorized to bind the organization you represent.\n"
source_yaml_url: https://artifacts.apis.io/mentlio/eligibility/mentlio-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Mentlio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Engineering Intelligence
- Token Optimization
- Enterprise
---
