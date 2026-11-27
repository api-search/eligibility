---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Site is intended solely for Users who, if they are a natural person, are eighteen (18) years of age or older
    type: individual
  minimum_age:
    text: This Site is intended solely for Users who, if they are a natural person, are eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Commercial use restricted
    text: solely for your personal, non-commercial use
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
name: Unison
provenance_date: '2026-11-10'
provider_name: Unison
provider_slug: unison
slug: unison-eligibility
source_date: '2026-11-10'
source_filename: unison-eligibility.yml
source_heading: Eligibility
source_page: https://www.unison.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unison\naid: unison\nurl: https://www.unison.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Site is intended solely for Users who, if they are a natural person, are eighteen (18) years of age\n    or older\nrestricted_uses:\n- summary: Commercial use restricted\n  text: solely for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Site is intended solely for Users who, if they are a natural person, are eighteen\
  \ (18) years of age\n    or older\n"
source_yaml_url: https://artifacts.apis.io/unison/eligibility/unison-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Unison's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Real Estate
- Home Equity
- Mortgage
- Consumer Finance
- Investment Management
---
