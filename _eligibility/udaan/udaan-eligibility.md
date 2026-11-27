---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Unless otherwise specified, the Products on the Platform are presented solely for the purpose of sale in India.
  minimum_age:
    text: Persons who are “incompetent to contract” within the meaning of the Indian Contract Act, 1872 including without limitation, minors, un-discharged insolvents, etc. are not eligible to use the Platform.
    value: null
  restricted_uses:
  - summary: Personal consumption purchases
    text: You will not use or access the Platform for your personal purposes and any Products that your purchase shall be for commercial purposes and not for personal consumption
  - summary: Dangerous Goods excluded
    text: “ Product(s) ” shall mean goods of any categories (other than Dangerous Goods).
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: udaan reserves the right to verify, approve, suspend, or reject any account at its discretion, including requesting additional information / documents for verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Udaan
provenance_date: '2026-11-10'
provider_name: Udaan
provider_slug: udaan
slug: udaan-eligibility
source_date: '2026-11-10'
source_filename: udaan-eligibility.yml
source_heading: Eligibility
source_page: https://udaan.com/s/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Udaan\naid: udaan\nurl: https://udaan.com/s/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Unless otherwise specified, the Products on the Platform are presented solely for the purpose of sale in\n    India.\nentity_types: []\nrestricted_uses:\n- summary: Personal consumption purchases\n  text: You will not use or access the Platform for your personal purposes and any Products that your purchase shall\n    be for commercial purposes and not for personal consumption\n- summary: Dangerous Goods excluded\n  text: “ Product(s) ” shall mean goods of any categories (other\
  \ than Dangerous Goods).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: udaan reserves the right to verify, approve, suspend, or reject any account at its discretion, including\n    requesting additional information / documents for verification.\nminimum_age:\n  value: null\n  text: Persons who are “incompetent to contract” within the meaning of the Indian Contract Act, 1872 including\n    without limitation, minors, un-discharged insolvents, etc. are not eligible to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/udaan/eligibility/udaan-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Udaan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- B2B
- E-Commerce
- Wholesale
- Retail
- India
- Supply Chain
---
