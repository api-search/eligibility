---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services for your internal business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal or household use
    text: You represent that you will not use them for personal, family or household purposes
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
name: Handoff
provenance_date: '2026-11-09'
provider_name: Handoff
provider_slug: handoff
slug: handoff-eligibility
source_date: '2026-11-09'
source_filename: handoff-eligibility.yml
source_heading: Eligibility
source_page: https://www.handoff.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Handoff\naid: handoff\nurl: https://www.handoff.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may use the Services for your internal business purposes.\nrestricted_uses:\n- summary: No personal or household use\n  text: You represent that you will not use them for personal, family or household purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/handoff/eligibility/handoff-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Handoff's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Construction Management
- Estimating
- Takeoffs
- Contractors
- Artificial Intelligence
- Project Management
- CRM
- Field Service Management
---
