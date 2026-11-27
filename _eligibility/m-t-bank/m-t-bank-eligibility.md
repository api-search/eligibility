---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Sites may not be available or may be limited in some jurisdictions outside the United States.
  entity_types:
  - text: any software that may be necessary to use the Sites for your personal use.
    type: individual
  minimum_age:
    text: The Sites are not intended to be used by European Union residents or users under the age of thirteen years.
    value: '13'
  restricted_uses:
  - summary: Unlawful internet gambling
    text: You agree not to use the Sites, products and/or services provided by M&T in a way that involves “restricted transactions” (as defined in Regulation GG, 12 CFR Part 233) pertaining to unlawful Internet gambling.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility for particular products and services is subject to M&T's review and acceptance.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: M&T Bank
provenance_date: '2026-11-10'
provider_name: M&T Bank
provider_slug: m-t-bank
slug: m-t-bank-eligibility
source_date: '2026-11-10'
source_filename: m-t-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.mtb.com/help-center/bank-policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: M&T Bank\naid: m-t-bank\nurl: https://www.mtb.com/help-center/bank-policies/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Sites may not be available or may be limited in some jurisdictions outside the United States.\nentity_types:\n- type: individual\n  text: any software that may be necessary to use the Sites for your personal use.\nrestricted_uses:\n- summary: Unlawful internet gambling\n  text: You agree not to use the Sites, products and/or services provided by M&T in a way that involves “restricted\n    transactions” (as defined in Regulation GG, 12 CFR Part\
  \ 233) pertaining to unlawful Internet gambling.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your eligibility for particular products and services is subject to M&T's review and acceptance.\nminimum_age:\n  value: '13'\n  text: The Sites are not intended to be used by European Union residents or users under the age of thirteen years.\n"
source_yaml_url: https://artifacts.apis.io/m-t-bank/eligibility/m-t-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from M&T Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Super-Regional Bank
- Treasury Management
- Payments
- Custody
- Fund Accounting
- Open Finance
---
