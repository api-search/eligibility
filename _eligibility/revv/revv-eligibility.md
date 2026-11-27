---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.
    type: individual
  minimum_age:
    text: You warrant to Us that You are aged 18 years or above
    value: '18'
  restricted_uses:
  - summary: No cookie tracking, ad exchanges, ad networks or data brokerage
    text: (f) use the Services for the purposes of cookie tracking, ad exchanges, ad networks or data brokerages.
  - summary: No export to restricted destinations or weapons uses
    text: You further agree not to use the Services for any purpose prohibited by applicable export laws and regulations, including without limitation, nuclear, chemical, or biological weapons proliferation
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
name: Revv
provenance_date: '2026-11-10'
provider_name: Revv
provider_slug: revv
slug: revv-eligibility
source_date: '2026-11-10'
source_filename: revv-eligibility.yml
source_heading: Eligibility
source_page: https://www.revv.so/termsofuse.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revv\naid: revv\nurl: https://www.revv.so/termsofuse.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.\nrestricted_uses:\n- summary: No cookie tracking, ad exchanges, ad networks or data brokerage\n  text: (f) use the Services for the purposes of cookie tracking, ad exchanges, ad networks or data brokerages.\n- summary: No export to restricted destinations or weapons uses\n  text: You further agree not to use the Services for any\
  \ purpose prohibited by applicable export laws and regulations,\n    including without limitation, nuclear, chemical, or biological weapons proliferation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You warrant to Us that You are aged 18 years or above\n"
source_yaml_url: https://artifacts.apis.io/revv/eligibility/revv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Revv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Document Automation
- E-Signature
- Contract Management
- Sales Enablement
- Workflow Automation
- Software-as-a-Service
---
