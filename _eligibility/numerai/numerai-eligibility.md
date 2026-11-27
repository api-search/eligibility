---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are (i) at least eighteen (18) years old
    type: individual
  minimum_age:
    text: You are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Financial activities requiring registration
    text: use the Services to carry out any financial activities subject to registration or licensing, including but not limited to using the Services to transact in securities
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
name: Numerai
provenance_date: '2026-11-10'
provider_name: Numerai
provider_slug: numerai
slug: numerai-eligibility
source_date: '2026-11-10'
source_filename: numerai-eligibility.yml
source_heading: Eligibility
source_page: https://numer.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Numerai\naid: numerai\nurl: https://numer.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are (i) at least eighteen (18) years old\nrestricted_uses:\n- summary: Financial activities requiring registration\n  text: use the Services to carry out any financial activities subject to registration or licensing, including but\n    not limited to using the Services to transact in securities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/numerai/eligibility/numerai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Numerai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Machine Learning
- Data Science
- Hedge Funds
- GraphQL
- Cryptocurrency
- Quantitative Finance
- Tournament
---
