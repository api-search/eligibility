---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be a resident of the United States and be 18 years or older to use the Services.
  entity_types:
  - text: You must be a resident of the United States and be 18 years or older to use the Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions compliance
    text: You agree that you will not use the Services in violation of any U.S. economic sanctions, anti-money-laundering, or counter-terrorism laws.
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
name: One
provenance_date: '2026-11-10'
provider_name: One
provider_slug: one
slug: one-eligibility
source_date: '2026-11-10'
source_filename: one-eligibility.yml
source_heading: Eligibility
source_page: https://www.onepay.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: One\naid: one\nurl: https://www.onepay.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be a resident of the United States and be 18 years or older to use the Services.\nentity_types:\n- type: individual\n  text: You must be a resident of the United States and be 18 years or older to use the Services.\nrestricted_uses:\n- summary: Sanctions compliance\n  text: You agree that you will not use the Services in violation of any U.S. economic sanctions, anti-money-laundering,\n    or counter-terrorism laws.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/one/eligibility/one-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from One's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Payments
- Consumer Finance
- Neobank
- Investing
- Cryptocurrency
---
