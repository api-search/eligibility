---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: provided for access and use only by persons located in the United States
  entity_types:
  - text: REPRESENT THAT YOU ARE EIGHTEEN (18) YEARS OF AGE OR OLDER
    type: individual
  minimum_age:
    text: REPRESENT THAT YOU ARE EIGHTEEN (18) YEARS OF AGE OR OLDER
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: for your personal, non-commercial use on a single mobile device
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may at any time require you to provide additional information in order to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ChangEd
provenance_date: '2026-11-09'
provider_name: ChangEd
provider_slug: changed
slug: changed-eligibility
source_date: '2026-11-09'
source_filename: changed-eligibility.yml
source_heading: Eligibility
source_page: https://www.gochanged.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChangEd\naid: changed\nurl: https://www.gochanged.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: provided for access and use only by persons located in the United States\nentity_types:\n- type: individual\n  text: REPRESENT THAT YOU ARE EIGHTEEN (18) YEARS OF AGE OR OLDER\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: for your personal, non-commercial use on a single mobile device\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may at any time require you to provide additional information\
  \ in order to verify your identity.\nminimum_age:\n  value: '18'\n  text: REPRESENT THAT YOU ARE EIGHTEEN (18) YEARS OF AGE OR OLDER\n"
source_yaml_url: https://artifacts.apis.io/changed/eligibility/changed-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ChangEd's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Debt Payoff
- Student Loans
- Personal Finance
- Savings
- Consumer App
---
