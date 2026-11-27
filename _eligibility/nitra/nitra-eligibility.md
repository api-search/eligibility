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
  restricted_uses:
  - summary: Fraudulent or criminal use
    text: Nitra determines on the basis of reasonable evidence that any Product is being used for fraudulent or criminal activities, or in violation of any applicable law or regulation
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
name: Nitra
provenance_date: '2026-11-10'
provider_name: Nitra
provider_slug: nitra
slug: nitra-eligibility
source_date: '2026-11-10'
source_filename: nitra-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.nitra.com/files/terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nitra\naid: nitra\nurl: https://cdn.nitra.com/files/terms-of-use.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or criminal use\n  text: Nitra determines on the basis of reasonable evidence that any Product is being used for fraudulent or criminal\n    activities, or in violation of any applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nitra/eligibility/nitra-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Nitra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Healthcare
- Fintech
- Banking
- Payments
- Practice Management
- Spend Management
---
