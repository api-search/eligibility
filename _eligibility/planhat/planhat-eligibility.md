---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated decisions about individuals
    text: You may not use the Services to make or support a decision about an individual that produces legal effects concerning that individual or similarly significantly affects them, unless you do so in accordance with applicable law on automated decision-making.
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
name: Planhat
provenance_date: '2026-11-10'
provider_name: Planhat
provider_slug: planhat
slug: planhat-eligibility
source_date: '2026-11-10'
source_filename: planhat-eligibility.yml
source_heading: Eligibility
source_page: https://www.planhat.com/legal/acceptable-use-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Planhat\naid: planhat\nurl: https://www.planhat.com/legal/acceptable-use-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated decisions about individuals\n  text: You may not use the Services to make or support a decision about an individual that produces legal effects\n    concerning that individual or similarly significantly affects them, unless you do so in accordance with applicable\n    law on automated decision-making.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/planhat/eligibility/planhat-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Planhat's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Customer Success
- Customer Platform
- CRM
- Customer Data
- Analytics
- Revenue
- MCP
---
