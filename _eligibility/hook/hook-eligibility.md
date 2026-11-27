---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you choose to access this site from locations outside the United Kingdom, you do so on your own initiative and are responsible for compliance with local laws.
  entity_types:
  - text: You are permitted to use the Website for your own personal, non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: You are permitted to use the Website for your own personal, non-commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some parts of the Website may require you to register to access and use them.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hook
provenance_date: '2026-11-09'
provider_name: Hook
provider_slug: hook
slug: hook-eligibility
source_date: '2026-11-09'
source_filename: hook-eligibility.yml
source_heading: Eligibility
source_page: https://hook.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hook\naid: hook\nurl: https://hook.co/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you choose to access this site from locations outside the United Kingdom, you do so on your own initiative\n    and are responsible for compliance with local laws.\nentity_types:\n- type: individual\n  text: You are permitted to use the Website for your own personal, non-commercial use.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You are permitted to use the Website for your own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Some parts of the Website may require you to register to access and use them.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hook/eligibility/hook-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Hook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Success
- AI Agents
- Churn Prediction
- Retention
- Net Revenue Retention
- Software-as-a-Service
- Artificial Intelligence
---
