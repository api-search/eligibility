---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: All Services are intended solely for Users who, if they are a natural person, are eighteen (18) years of age or older
    type: individual
  minimum_age:
    text: eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: No automated data collection
    text: use any automated means to access this Site or collect any information from the Site
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Credit products are subject to credit approval and may be subject to sufficient investor commitment.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LendingClub
provenance_date: '2026-11-09'
provider_name: LendingClub
provider_slug: lendingclub
slug: lendingclub-eligibility
source_date: '2026-11-09'
source_filename: lendingclub-eligibility.yml
source_heading: Eligibility
source_page: https://www.happen.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LendingClub\naid: lendingclub\nurl: https://www.happen.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: All Services are intended solely for Users who, if they are a natural person, are eighteen (18) years of\n    age or older\nrestricted_uses:\n- summary: No automated data collection\n  text: use any automated means to access this Site or collect any information from the Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Credit products are subject to credit approval and may be\
  \ subject to sufficient investor commitment.\nminimum_age:\n  value: '18'\n  text: eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/lendingclub/eligibility/lendingclub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from LendingClub's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Personal Loans
- Banking
- Financial Services
- Marketplace Lending
- Consumer Lending
---
