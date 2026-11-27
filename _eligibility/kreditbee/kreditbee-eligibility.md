---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: legally allowed to enter into a contract and avail the Services in India
  entity_types:
  - text: the User is a natural/ legal person who has attained the age of at least 21 (twenty-one) years of age
    type: individual
  minimum_age:
    text: has attained the age of at least 21 (twenty-one) years of age
    value: '21'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You may be required to provide certain KYC documentation and other information as may be required by KreditBee and/ or the Gold Partners
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: KreditBee
provenance_date: '2026-11-09'
provider_name: KreditBee
provider_slug: kreditbee
slug: kreditbee-eligibility
source_date: '2026-11-09'
source_filename: kreditbee-eligibility.yml
source_heading: Eligibility
source_page: https://www.kreditbee.in/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KreditBee\naid: kreditbee\nurl: https://www.kreditbee.in/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: legally allowed to enter into a contract and avail the Services in India\nentity_types:\n- type: individual\n  text: the User is a natural/ legal person who has attained the age of at least 21 (twenty-one) years of age\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You may be required to provide certain KYC documentation and other information as may be required by KreditBee\n    and/\
  \ or the Gold Partners\nminimum_age:\n  value: '21'\n  text: has attained the age of at least 21 (twenty-one) years of age\n"
source_yaml_url: https://artifacts.apis.io/kreditbee/eligibility/kreditbee-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from KreditBee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Digital Lending
- Personal Loans
- Consumer Credit
- NBFC
- Credit Score
- India
- Mobile
---
