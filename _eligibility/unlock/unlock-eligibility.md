---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is controlled and operated within the United States and is not intended for use outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No business or commercial use
    text: not for use for any business purpose or commercial activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All transactions are subject to verification of your identity, property value, home insurance, title, and outstanding property liens.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unlock
provenance_date: '2026-11-10'
provider_name: Unlock
provider_slug: unlock
slug: unlock-eligibility
source_date: '2026-11-10'
source_filename: unlock-eligibility.yml
source_heading: Eligibility
source_page: https://www.unlock.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unlock\naid: unlock\nurl: https://www.unlock.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is controlled and operated within the United States and is not intended for use outside of the\n    United States.\nentity_types: []\nrestricted_uses:\n- summary: No business or commercial use\n  text: not for use for any business purpose or commercial activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All transactions are subject to verification of your identity, property value, home insurance, title, and\n    outstanding\
  \ property liens.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unlock/eligibility/unlock-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Unlock's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Home Equity
- Mortgage
- Real Estate
- Consumer Lending
- Home Equity Agreement
- Personal Finance
- Content
---
