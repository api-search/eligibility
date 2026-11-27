---
api_specs:
- filename: PostmanCollection
  format: yaml
  label: Sumsub API
  slug: sumsub-api
  spec_type: Postman
  url: https://github.com/SumSubstance/PostmanCollection
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may only use the Websites if you are 16 years of age or older.
    value: '16'
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
name: Sumsub
provenance_date: '2026-11-10'
provider_name: Sumsub
provider_slug: sumsub
slug: sumsub-eligibility
source_date: '2026-11-10'
source_filename: sumsub-eligibility.yml
source_heading: Eligibility
source_page: https://sumsub.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sumsub\naid: sumsub\nurl: https://sumsub.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may only use the Websites if you are 16 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/sumsub/eligibility/sumsub-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Sumsub's own page on 2026-11-10.
synthetic: false
tags:
- AML
- Compliance
- Fraud Prevention
- Identity Verification
- KYB
- KYC
- Transaction Monitoring
- Travel Rule
---
