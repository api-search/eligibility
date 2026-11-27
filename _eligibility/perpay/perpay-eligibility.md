---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'Registration Data: You represent that you are: (i) 18 years of age or older (ii) a U.S. resident'
  entity_types:
  - text: 'you represent that you are: (i) 18 years of age or older (ii) a U.S. resident (iii) able to form a binding contract with Perpay'
    type: individual
  minimum_age:
    text: 'You represent that you are: (i) 18 years of age or older'
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: Perpay grants you a limited right to access and use the Services for your own personal, non-commercial and internal use only.
  - summary: No resale of products
    text: any resale of Products for personal and/or business profit is strictly prohibited.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your ability to use your initial spending limit to make purchases on the Marketplace is subject to approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Perpay
provenance_date: '2026-11-10'
provider_name: Perpay
provider_slug: perpay
slug: perpay-eligibility
source_date: '2026-11-10'
source_filename: perpay-eligibility.yml
source_heading: Eligibility
source_page: https://perpay.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Perpay\naid: perpay\nurl: https://perpay.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'Registration Data: You represent that you are: (i) 18 years of age or older (ii) a U.S. resident'\nentity_types:\n- type: individual\n  text: 'you represent that you are: (i) 18 years of age or older (ii) a U.S. resident (iii) able to form a binding\n    contract with Perpay'\nrestricted_uses:\n- summary: Personal use only\n  text: Perpay grants you a limited right to access and use the Services for your own personal, non-commercial and\n\
  \    internal use only.\n- summary: No resale of products\n  text: any resale of Products for personal and/or business profit is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your ability to use your initial spending limit to make purchases on the Marketplace is subject to approval.\nminimum_age:\n  value: '18'\n  text: 'You represent that you are: (i) 18 years of age or older'\n"
source_yaml_url: https://artifacts.apis.io/perpay/eligibility/perpay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Perpay's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Buy Now Pay Later
- Credit Building
- Payroll Deduction
- Payments
- Consumer Finance
---
