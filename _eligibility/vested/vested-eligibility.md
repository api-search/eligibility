---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: INDIVIDUALS UNDER THE AGE OF 18 ARE NOT PERMITTED TO SUBSCRIBE TO ANY OF OUR SERVICES.
    value: '18'
  restricted_uses:
  - summary: Funds linked to crime
    text: You represent and warrant that none of the money you transfer to and/or invest through the Platform comes from, or will be used to promote the conduct of, any crime or other illegal activity.
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
name: Vested
provenance_date: '2026-11-10'
provider_name: Vested
provider_slug: vested
slug: vested-eligibility
source_date: '2026-11-10'
source_filename: vested-eligibility.yml
source_heading: Eligibility
source_page: https://vestedfinance.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vested\naid: vested\nurl: https://vestedfinance.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Funds linked to crime\n  text: You represent and warrant that none of the money you transfer to and/or invest through the Platform comes\n    from, or will be used to promote the conduct of, any crime or other illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: INDIVIDUALS UNDER THE AGE OF 18 ARE NOT PERMITTED\
  \ TO SUBSCRIBE TO ANY OF OUR SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/vested/eligibility/vested-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Vested's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Investing
- Stocks
- ETFs
- Wealth Management
- Brokerage
- India
- US Markets
---
