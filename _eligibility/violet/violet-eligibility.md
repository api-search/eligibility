---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Service is unavailable where prohibited by law. Violet will use its sole and absolute discretion to revise the list of prohibited jurisdictions
  entity_types:
  - text: you represent that (1) you are at least 18 years of age or older (for US-based users) or older than the age of majority in the jurisdiction in which you reside
    type: individual
  - text: For corporate entities, we may require identification information related to the directors, officers or equity owners of the business.
    type: business
  minimum_age:
    text: you are at least 18 years of age or older (for US-based users) or older than the age of majority in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Illegal transactions
    text: You agree to comply with applicable law and not to use Violet for any transaction or activity that violates applicable laws, regulations or rules.
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
name: Violet
provenance_date: '2026-11-10'
provider_name: Violet
provider_slug: violet
slug: violet-eligibility
source_date: '2026-11-10'
source_filename: violet-eligibility.yml
source_heading: Eligibility
source_page: https://www.violet.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Violet\naid: violet\nurl: https://www.violet.co/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Service is unavailable where prohibited by law. Violet will use its sole and absolute discretion to revise\n    the list of prohibited jurisdictions\nentity_types:\n- type: individual\n  text: you represent that (1) you are at least 18 years of age or older (for US-based users) or older than the\n    age of majority in the jurisdiction in which you reside\n- type: business\n  text: For corporate entities, we may require identification information related to the directors,\
  \ officers or\n    equity owners of the business.\nrestricted_uses:\n- summary: Illegal transactions\n  text: You agree to comply with applicable law and not to use Violet for any transaction or activity that violates\n    applicable laws, regulations or rules.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age or older (for US-based users) or older than the age of majority in the\n    jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/violet/eligibility/violet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Violet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- Identity
- DeFi
- Blockchain
- KYC
- AML
- Web3
- Decentralized Identity
- Sanctions Screening
- OAuth
- Authentication
---
