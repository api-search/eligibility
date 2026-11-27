---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Foundation Personal, this license is limited to your personal, non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Services for any unlawful purpose or in violation of any applicable laws or regulations.
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
name: Mallory
provenance_date: '2026-11-10'
provider_name: Mallory
provider_slug: mallory
slug: mallory-eligibility
source_date: '2026-11-10'
source_filename: mallory-eligibility.yml
source_heading: Eligibility
source_page: https://mallory.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mallory\naid: mallory\nurl: https://mallory.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you use Foundation Personal, this license is limited to your personal, non-commercial use.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Services for any unlawful purpose or in violation of any applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mallory/eligibility/mallory-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Mallory's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Threat Intelligence
- Artificial Intelligence
- Platform
- Exposure Management
---
