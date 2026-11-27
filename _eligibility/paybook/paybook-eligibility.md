---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Site and the Services are offered and available to users who are 18 years of age or older.
    type: individual
  - text: corporate customers who use our APIs and services on behalf of their end-users
    type: business
  minimum_age:
    text: This Site and the Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You agree not to export or re-export the Services or the underlying software or intellectual property.
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
name: Paybook
provenance_date: '2026-11-10'
provider_name: Paybook
provider_slug: paybook
slug: paybook-eligibility
source_date: '2026-11-10'
source_filename: paybook-eligibility.yml
source_heading: Eligibility
source_page: https://help.paybook.com/en/article/terms-of-use-183zl4u/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paybook\naid: paybook\nurl: https://help.paybook.com/en/article/terms-of-use-183zl4u/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Site and the Services are offered and available to users who are 18 years of age or older.\n- type: business\n  text: corporate customers who use our APIs and services on behalf of their end-users\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree not to export or re-export the Services or the underlying software or intellectual property.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Site and the Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/paybook/eligibility/paybook-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Paybook's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Data Aggregation
- Banking
---
