---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is offered and available to Users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
  minimum_age:
    text: This Website is offered and available to Users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No legal advice
    text: The Services do not include or constitute legal advice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users authorize Azibo, directly or through third parties, to make any inquiries we consider necessary to validate your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zibo
provenance_date: '2026-11-10'
provider_name: Zibo
provider_slug: zibo
slug: zibo-eligibility
source_date: '2026-11-10'
source_filename: zibo-eligibility.yml
source_heading: Eligibility
source_page: https://www.azibo.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zibo\naid: zibo\nurl: https://www.azibo.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is offered and available to Users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\nentity_types: []\nrestricted_uses:\n- summary: No legal advice\n  text: The Services do not include or constitute legal advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users authorize Azibo, directly or through third parties, to make any inquiries we consider necessary to\n    validate\
  \ your identity.\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to Users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/zibo/eligibility/zibo-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Zibo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Property Management
- Real Estate
- Rentals
- Fintech
- Landlord Software
- Rent Collection
- Banking
- Accounting
---
