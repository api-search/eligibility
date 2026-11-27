---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account is for one person.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use Aimgod.
    value: '16'
  restricted_uses:
  - summary: Under-16 use restricted
    text: You must be at least 16 years old to use Aimgod.
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
name: Aimgod
provenance_date: '2026-11-09'
provider_name: Aimgod
provider_slug: aimgod-com
slug: aimgod-com-eligibility
source_date: '2026-11-09'
source_filename: aimgod-com-eligibility.yml
source_heading: Eligibility
source_page: https://aimgod.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aimgod\naid: aimgod-com\nurl: https://aimgod.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account is for one person.\nrestricted_uses:\n- summary: Under-16 use restricted\n  text: You must be at least 16 years old to use Aimgod.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use Aimgod.\n"
source_yaml_url: https://artifacts.apis.io/aimgod-com/eligibility/aimgod-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aimgod's own page on 2026-11-09.
synthetic: false
tags:
- Productivity
- Artificial Intelligence
- Planner
- Team Collaboration
- Personal
---
