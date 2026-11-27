---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: You must be at least 18 years old and a resident of India to use our Services.
  entity_types:
  - text: You must be at least 18 years old and a resident of India to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and a resident of India to use our Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Use our Services for any illegal or unauthorized purpose.
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
name: Bachatt
provenance_date: '2026-11-09'
provider_name: Bachatt
provider_slug: bachatt
slug: bachatt-eligibility
source_date: '2026-11-09'
source_filename: bachatt-eligibility.yml
source_heading: Eligibility
source_page: https://www.bachatt.app/policies/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bachatt\naid: bachatt\nurl: https://www.bachatt.app/policies/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: You must be at least 18 years old and a resident of India to use our Services.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and a resident of India to use our Services.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Use our Services for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18 years old and a resident of India to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/bachatt/eligibility/bachatt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bachatt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Savings
- Mutual Funds
- Investment
- Lending
- India
- Consumer Finance
---
