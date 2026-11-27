---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'if you are an individual and you access or use our Service on behalf of a company or other entity, such as your employer (together with its affiliates, an “Organization”), then: (a) these Terms are an agreement between us and you and us and that Organization'
    type: business
  minimum_age:
    text: To use our Service, you must be at least thirteen (13) years of age.
    value: '13'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You agree to comply with all applicable export and re-export control and trade and economic sanctions laws
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
name: Relevize
provenance_date: '2026-11-10'
provider_name: Relevize
provider_slug: relevize
slug: relevize-eligibility
source_date: '2026-11-10'
source_filename: relevize-eligibility.yml
source_heading: Eligibility
source_page: https://www.relevize.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Relevize\naid: relevize\nurl: https://www.relevize.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'if you are an individual and you access or use our Service on behalf of a company or other entity, such\n    as your employer (together with its affiliates, an “Organization”), then: (a) these Terms are an agreement between\n    us and you and us and that Organization'\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You agree to comply with all applicable export and re-export control and trade and economic\
  \ sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To use our Service, you must be at least thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/relevize/eligibility/relevize-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Relevize's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Partner Marketing
- Channel Marketing
- Market Development Funds
- MDF
- Partner Incentives
- Expense Management
- Payments
- Demand Generation
- Software-as-a-Service
---
