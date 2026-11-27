---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: To be eligible to use the Services, you must i) reside in Canada and have a valid Canadian mobile phone number (excluding IP telephony)
  entity_types:
  - text: be at least 18 years old, and iii) have the legal capacity to hold an Account
    type: individual
  - text: If you are agreeing to the terms of this Agreement on behalf of an organization (corporation, trust, partnership or any similar entity) (a “ Business Account ”), both you as an individual and your organization are legally bound by the terms of this Agreement.
    type: business
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Banned business categories
    text: the following categories of businesses, business practices, and sale items are banned from using the Services
  - summary: Multi-level marketing and high-risk businesses
    text: J. Multi-level marketing; K. Unfair, predatory or deceptive practices; or L. Other high risk businesses (as determined by Shakepay).
  - summary: Personal account used for business
    text: the use of your personal Shakepay Account for business purposes is prohibited
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: During the sign-up process of your Account, or at any other time deemed necessary by Shakepay, you agree to provide us with, and consent to the processing of, any personal information we may request for the purposes of identity verification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shakepay
provenance_date: '2026-11-10'
provider_name: Shakepay
provider_slug: shakepay
slug: shakepay-eligibility
source_date: '2026-11-10'
source_filename: shakepay-eligibility.yml
source_heading: Eligibility
source_page: https://legal.shakepay.com/master
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shakepay\naid: shakepay\nurl: https://legal.shakepay.com/master\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: To be eligible to use the Services, you must i) reside in Canada and have a valid Canadian mobile phone\n    number (excluding IP telephony)\nentity_types:\n- type: individual\n  text: be at least 18 years old, and iii) have the legal capacity to hold an Account\n- type: business\n  text: If you are agreeing to the terms of this Agreement on behalf of an organization (corporation, trust, partnership\n    or any similar entity) (a “ Business Account\
  \ ”), both you as an individual and your organization are legally\n    bound by the terms of this Agreement.\nrestricted_uses:\n- summary: Banned business categories\n  text: the following categories of businesses, business practices, and sale items are banned from using the Services\n- summary: Multi-level marketing and high-risk businesses\n  text: J. Multi-level marketing; K. Unfair, predatory or deceptive practices; or L. Other high risk businesses\n    (as determined by Shakepay).\n- summary: Personal account used for business\n  text: the use of your personal Shakepay Account for business purposes is prohibited\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: During the sign-up process of your Account, or at any other time deemed necessary by Shakepay, you agree\n    to provide us with, and consent to the processing of, any personal information we may request for the purposes\n    of identity verification\nminimum_age:\n  value: '18'\n  text: be at least\
  \ 18 years old\n"
source_yaml_url: https://artifacts.apis.io/shakepay/eligibility/shakepay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Shakepay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Cryptocurrency
- Bitcoin
- Financial Services
- Canada
- Fintech
---
