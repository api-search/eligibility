---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: you are in, under the control of, or a national or resident of Cuba, Iran, North Korea, Sudan, or Syria or any other country subject to United States embargo, UN sanctions, the European Union or HM Treasury's financial sanctions regimes
  minimum_age:
    text: at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No use on behalf of third parties
    text: By using Services, you agree and represent that you will use the Services only for yourself, and not on behalf of any third party.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: We may request certain personal information from you including, but not limited to, your name, address, telephone number, email address, date of birth, taxpayer identification number, government identification number
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MoonPay
provenance_date: '2026-11-10'
provider_name: MoonPay
provider_slug: moonpay
slug: moonpay-eligibility
source_date: '2026-11-10'
source_filename: moonpay-eligibility.yml
source_heading: Eligibility
source_page: https://www.moonpay.com/legal/terms_of_use_jersey
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MoonPay\naid: moonpay\nurl: https://www.moonpay.com/legal/terms_of_use_jersey\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: you are in, under the control of, or a national or resident of Cuba, Iran, North Korea, Sudan, or Syria\n    or any other country subject to United States embargo, UN sanctions, the European Union or HM Treasury's financial\n    sanctions regimes\nentity_types: []\nrestricted_uses:\n- summary: No use on behalf of third parties\n  text: By using Services, you agree and represent that you will use the Services\
  \ only for yourself, and not on\n    behalf of any third party.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: We may request certain personal information from you including, but not limited to, your name, address,\n    telephone number, email address, date of birth, taxpayer identification number, government identification number\nminimum_age:\n  value: '18'\n  text: at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/moonpay/eligibility/moonpay-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from MoonPay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Crypto Infrastructure
- Payments
- Cryptocurrency
- On-Ramp
- Off-Ramp
- Fintech
- Digital Wallet
- Blockchain
- KYC
---
