---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you've received your parent's or guardian's permission to use the Services
    type: individual
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from individuals under 18; if you are under the age of 18, please do not attempt to register for the Services
    value: '18'
  restricted_uses:
  - summary: No credit/FCRA eligibility use
    text: MM bears no authority to evaluate your eligibility for any of the following products, services or transactions
  - summary: No commercial use on behalf of third parties
    text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
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
name: Monarch Money
provenance_date: '2026-11-10'
provider_name: Monarch Money
provider_slug: monarch-money
slug: monarch-money-eligibility
source_date: '2026-11-10'
source_filename: monarch-money-eligibility.yml
source_heading: Eligibility
source_page: https://www.monarch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Monarch Money\naid: monarch-money\nurl: https://www.monarch.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you've received your parent's or guardian's permission to use the Services\nrestricted_uses:\n- summary: No credit/FCRA eligibility use\n  text: MM bears no authority to evaluate your eligibility for any of the following products, services or transactions\n- summary: No commercial use on behalf of third parties\n\
  \  text: You will only use the Services for your own internal, personal, non-commercial use, and not on behalf of\n    or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not knowingly collect or solicit personally identifiable information from individuals under 18; if\n    you are under the age of 18, please do not attempt to register for the Services\n"
source_yaml_url: https://artifacts.apis.io/monarch-money/eligibility/monarch-money-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Monarch Money's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Personal Finance
- Budgeting
- Money Management
- Consumer
- Trust Center
---
