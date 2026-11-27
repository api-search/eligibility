---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You must meet the following requirements to use our Services: Be at least 18 years of age'
    type: individual
  minimum_age:
    text: Be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited purposes
    text: You will not use the Services for any unlawful or prohibited purpose
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
name: Standout
provenance_date: '2026-11-10'
provider_name: Standout
provider_slug: standout
slug: standout-eligibility
source_date: '2026-11-10'
source_filename: standout-eligibility.yml
source_heading: Eligibility
source_page: https://standout.work/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Standout\naid: standout\nurl: https://standout.work/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You must meet the following requirements to use our Services: Be at least 18 years of age'\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: You will not use the Services for any unlawful or prohibited purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/standout/eligibility/standout-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Standout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hiring
- Recruiting
- Talent
- Job
- AI Agents
- Developer Tools
---
