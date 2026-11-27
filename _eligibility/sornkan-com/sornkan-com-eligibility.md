---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You must pass identity verification (KYC) before receiving payouts, and the bank account name must match yours.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: sornkan-com
provenance_date: '2026-11-10'
provider_name: sornkan-com
provider_slug: sornkan-com
slug: sornkan-com-eligibility
source_date: '2026-11-10'
source_filename: sornkan-com-eligibility.yml
source_heading: Eligibility
source_page: https://sornkan.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sornkan-com\naid: sornkan-com\nurl: https://sornkan.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You must pass identity verification (KYC) before receiving payouts, and the bank account name must match\n    yours.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sornkan-com/eligibility/sornkan-com-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from sornkan-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
