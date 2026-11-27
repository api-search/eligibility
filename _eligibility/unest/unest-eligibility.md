---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The UNest Platform is intended solely for use by individuals located in the United States.
  entity_types:
  - text: The UNest Platform is intended solely for use by individuals who are age 18 or older.
    type: individual
  minimum_age:
    text: The UNest Platform is intended solely for use by individuals who are age 18 or older.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You further agree that you will use the UNest Platform solely for your personal, non-commercial use
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
name: UNest
provenance_date: '2026-11-10'
provider_name: UNest
provider_slug: unest
slug: unest-eligibility
source_date: '2026-11-10'
source_filename: unest-eligibility.yml
source_heading: Eligibility
source_page: https://unest.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UNest\naid: unest\nurl: https://unest.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The UNest Platform is intended solely for use by individuals located in the United States.\nentity_types:\n- type: individual\n  text: The UNest Platform is intended solely for use by individuals who are age 18 or older.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You further agree that you will use the UNest Platform solely for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The UNest Platform is intended solely for use by individuals who are age 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/unest/eligibility/unest-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from UNest's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Investing
- Custodial Accounts
- Savings
- Insurance
- Family Finance
---
