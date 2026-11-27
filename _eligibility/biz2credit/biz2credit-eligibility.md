---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Biz2credit makes no representations that the Service are appropriate or available for use in jurisdictions other than the United States. You may not use the Services if you are a resident of a country embargoed by the United States
  entity_types:
  - text: By accessing Services, you represent that you are 18 years of age or older.
    type: individual
  - text: you affirm that you are obtaining services solely for commercial or business purposes and not for personal, family, or household use.
    type: business
  minimum_age:
    text: By accessing Services, you represent that you are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: You will not use the Services for any unauthorized or unlawful purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Federal law requires all financial institutions to obtain, verify, and record information that identifies each person who opens an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Biz2Credit
provenance_date: '2026-11-09'
provider_name: Biz2Credit
provider_slug: biz2credit
slug: biz2credit-eligibility
source_date: '2026-11-09'
source_filename: biz2credit-eligibility.yml
source_heading: Eligibility
source_page: https://www.biz2credit.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biz2Credit\naid: biz2credit\nurl: https://www.biz2credit.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Biz2credit makes no representations that the Service are appropriate or available for use in jurisdictions\n    other than the United States. You may not use the Services if you are a resident of a country embargoed by the\n    United States\nentity_types:\n- type: individual\n  text: By accessing Services, you represent that you are 18 years of age or older.\n- type: business\n  text: you affirm that you are obtaining services solely for commercial or business\
  \ purposes and not for personal,\n    family, or household use.\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: You will not use the Services for any unauthorized or unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Federal law requires all financial institutions to obtain, verify, and record information that identifies\n    each person who opens an account.\nminimum_age:\n  value: '18'\n  text: By accessing Services, you represent that you are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/biz2credit/eligibility/biz2credit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Biz2Credit's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Lending
- Small Business
- Online Loans
- Credit
---
