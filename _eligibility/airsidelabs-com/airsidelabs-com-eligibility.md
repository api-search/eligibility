---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account is for one person or one organisation.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Aviation operations and safety-critical decisions
    text: they must not be relied on for flight operations, air traffic control, safety-critical decisions or anything where an error could cause harm
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
name: Airside Labs
provenance_date: '2026-11-09'
provider_name: Airside Labs
provider_slug: airsidelabs-com
slug: airsidelabs-com-eligibility
source_date: '2026-11-09'
source_filename: airsidelabs-com-eligibility.yml
source_heading: Eligibility
source_page: https://airsidelabs.com/tools/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airside Labs\naid: airsidelabs-com\nurl: https://airsidelabs.com/tools/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account is for one person or one organisation.\nrestricted_uses:\n- summary: Aviation operations and safety-critical decisions\n  text: they must not be relied on for flight operations, air traffic control, safety-critical decisions or anything\n    where an error could cause harm\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airsidelabs-com/eligibility/airsidelabs-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Airside Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Aviation
- Travel
- Infrastructure
- Platform
---
