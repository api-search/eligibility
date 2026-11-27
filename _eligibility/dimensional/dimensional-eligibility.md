---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least the legal age of majority in your jurisdiction.
    type: individual
  minimum_age:
    text: You represent that you are at least the legal age of majority in your jurisdiction.
    value: age of majority
  restricted_uses:
  - summary: Export restrictions
    text: You shall not export App or any of the Platform, Services or Content, or any information about any of them without the prior written consent of Dimensional
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
name: Dimensional
provenance_date: '2026-11-09'
provider_name: Dimensional
provider_slug: dimensional
slug: dimensional-eligibility
source_date: '2026-11-09'
source_filename: dimensional-eligibility.yml
source_heading: Eligibility
source_page: https://about.dimensional.me/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dimensional\naid: dimensional\nurl: https://about.dimensional.me/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least the legal age of majority in your jurisdiction.\nrestricted_uses:\n- summary: Export restrictions\n  text: You shall not export App or any of the Platform, Services or Content, or any information about any of them\n    without the prior written consent of Dimensional\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ age of majority\n  text: You represent that you are at least the legal age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/dimensional/eligibility/dimensional-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dimensional's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Personality Science
- Psychology
- Consumer
- Mobile App
- Social
- Relationships
- Assessment
---
