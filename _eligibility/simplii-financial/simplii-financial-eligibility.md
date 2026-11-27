---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree that your account will only be used for personal purposes.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No business use
    text: You agree that you will not use your account for any business that you own or in which you have any interest.
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
name: Simplii Financial
provenance_date: '2026-11-10'
provider_name: Simplii Financial
provider_slug: simplii-financial
slug: simplii-financial-eligibility
source_date: '2026-11-10'
source_filename: simplii-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.simplii.com/en/legal.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simplii Financial\naid: simplii-financial\nurl: https://www.simplii.com/en/legal.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You agree that your account will only be used for personal purposes.\nrestricted_uses:\n- summary: No business use\n  text: You agree that you will not use your account for any business that you own or in which you have any interest.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/simplii-financial/eligibility/simplii-financial-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Simplii Financial's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Digital Bank
- Direct Banking
- Big Six
- CIBC
- Consumer-Driven Banking
---
