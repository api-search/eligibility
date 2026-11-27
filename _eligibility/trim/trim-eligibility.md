---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you've received your parent's or guardian's permission to use the Services
    value: null
  restricted_uses:
  - summary: Non-commercial only
    text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to sign up for an account, and select a password and user name
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Trim
provenance_date: '2026-11-10'
provider_name: Trim
provider_slug: trim
slug: trim-eligibility
source_date: '2026-11-10'
source_filename: trim-eligibility.yml
source_heading: Eligibility
source_page: https://www.onemainmymoney.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trim\naid: trim\nurl: https://www.onemainmymoney.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Non-commercial only\n  text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of\n    or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to sign up for an account, and select\
  \ a password and user name\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you've received your parent's or guardian's permission to use the Services\n"
source_yaml_url: https://artifacts.apis.io/trim/eligibility/trim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Trim's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Personal Finance
- Subscription Management
- Bill Negotiation
- Savings
- Consumer Finance
---
