---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - PH
    text: you are citizen or legal resident of the Philippines
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Services.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You will only use the Services for your own personal and non-commercial use
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You hereby authorize Zed, directly or through third parties, to make any inquiries we consider necessary to validate your identity and/or authenticate your identity and Account information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zed
provenance_date: '2026-11-10'
provider_name: Zed
provider_slug: zed
slug: zed-eligibility
source_date: '2026-11-10'
source_filename: zed-eligibility.yml
source_heading: Eligibility
source_page: https://www.zed.co/user-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zed\naid: zed\nurl: https://www.zed.co/user-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - PH\n  excluded: []\n  text: you are citizen or legal resident of the Philippines\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Services.\nrestricted_uses:\n- summary: No commercial use\n  text: You will only use the Services for your own personal and non-commercial use\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You hereby authorize Zed, directly or through third parties, to make any inquiries we consider necessary\n\
  \    to validate your identity and/or authenticate your identity and Account information.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/zed/eligibility/zed-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Zed's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit Cards
- Payments
- Mastercard
- Consumer Finance
- Virtual Cards
- Mobile Banking
- Philippines
- Southeast Asia
---
