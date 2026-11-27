---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create and account, you must be 18 years old and provide correct, current, and complete information about yourself.
    type: individual
  minimum_age:
    text: To create and account, you must be 18 years old
    value: '18'
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
name: Prodly
provenance_date: '2026-11-10'
provider_name: Prodly
provider_slug: prodly
slug: prodly-eligibility
source_date: '2026-11-10'
source_filename: prodly-eligibility.yml
source_heading: Eligibility
source_page: https://www.prodly.co/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prodly\naid: prodly\nurl: https://www.prodly.co/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create and account, you must be 18 years old and provide correct, current, and complete information about\n    yourself.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To create and account, you must be 18 years old\n"
source_yaml_url: https://artifacts.apis.io/prodly/eligibility/prodly-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Prodly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Salesforce
- DevOps
- Deployment
- Data Migration
- Release Management
- Version Control
- CLI
- Compliance
- Developer Tools
---
