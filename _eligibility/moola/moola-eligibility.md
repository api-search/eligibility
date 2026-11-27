---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are a citizen, resident, or member of any jurisdiction or group that is subject to economic sanctions by the United States or other countries, then you are not authorized to use the Services.
  entity_types:
  - text: You will only use the Services for your own personal use, and not on behalf of or for the benefit of any third party
    type: individual
  minimum_age:
    text: Ages 18 and Over Only. The Site is intended for those ages 18 and over.
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions
    text: if you are a citizen, resident, or member of any jurisdiction or group that is subject to economic sanctions by the United States or other countries, then you are not authorized to use the Services.
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
name: Moola
provenance_date: '2026-11-10'
provider_name: Moola
provider_slug: moola
slug: moola-eligibility
source_date: '2026-11-10'
source_filename: moola-eligibility.yml
source_heading: Eligibility
source_page: https://app.moola.market/#/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moola\naid: moola\nurl: https://app.moola.market/#/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are a citizen, resident, or member of any jurisdiction or group that is subject to economic sanctions\n    by the United States or other countries, then you are not authorized to use the Services.\nentity_types:\n- type: individual\n  text: You will only use the Services for your own personal use, and not on behalf of or for the benefit of any\n    third party\nrestricted_uses:\n- summary: Sanctioned jurisdictions\n  text: if you are a citizen, resident, or member of any\
  \ jurisdiction or group that is subject to economic sanctions\n    by the United States or other countries, then you are not authorized to use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Ages 18 and Over Only. The Site is intended for those ages 18 and over.\n"
source_yaml_url: https://artifacts.apis.io/moola/eligibility/moola-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Moola's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DeFi
- Lending
- Borrowing
- Yield
- Flash Loans
- Celo
- Blockchain
- Smart Contracts
- Cryptocurrency
---
