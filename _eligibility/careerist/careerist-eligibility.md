---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are available only to individuals who are at least eighteen (18) years of age and are located in the United States.
  entity_types:
  - text: The Services are available only to individuals who are at least eighteen (18) years of age and are located in the United States.
    type: individual
  minimum_age:
    text: at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Commercial use of materials
    text: use the materials for any commercial purpose
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
name: Careerist
provenance_date: '2026-11-09'
provider_name: Careerist
provider_slug: careerist
slug: careerist-eligibility
source_date: '2026-11-09'
source_filename: careerist-eligibility.yml
source_heading: Eligibility
source_page: https://careerist.cc/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Careerist\naid: careerist\nurl: https://careerist.cc/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are available only to individuals who are at least eighteen (18) years of age and are located\n    in the United States.\nentity_types:\n- type: individual\n  text: The Services are available only to individuals who are at least eighteen (18) years of age and are located\n    in the United States.\nrestricted_uses:\n- summary: Commercial use of materials\n  text: use the materials for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/careerist/eligibility/careerist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Careerist's own page on 2026-11-09.
synthetic: false
tags:
- Tech Education
- Career Training
- AI Automation
- Internship
- Career Coaching
---
