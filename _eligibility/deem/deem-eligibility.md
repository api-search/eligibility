---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Certain Websites allow users to register for an account and password ("Enrolled Users").
    type: individual
  - text: certain services may be available only to employees of "Participating Companies," which are companies that have entered into agreements with Deem
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Impersonation or false identity
    text: not impersonate another enrolled user or provide false identity information to gain access to or use the service.
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
name: Deem
provenance_date: '2026-11-09'
provider_name: Deem
provider_slug: deem
slug: deem-eligibility
source_date: '2026-11-09'
source_filename: deem-eligibility.yml
source_heading: Eligibility
source_page: https://www.deem.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deem\naid: deem\nurl: https://www.deem.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Certain Websites allow users to register for an account and password (\"Enrolled Users\").\n- type: business\n  text: certain services may be available only to employees of \"Participating Companies,\" which are companies that\n    have entered into agreements with Deem\nrestricted_uses:\n- summary: Impersonation or false identity\n  text: not impersonate another enrolled user or provide false identity information to gain access\
  \ to or use the\n    service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deem/eligibility/deem-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Deem's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Software-as-a-Service
- Corporate Travel
- Expense Management
- Automation
---
