---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Codacash is available only to residents of listed Codacash Territories: Indonesia, Korea, Turkey, Thailand, Brazil, Malaysia, Philippines.'
  minimum_age:
    text: The Services are not directed to persons under the age of majority in your country (a “minor” ).
    value: age of majority in your country
  restricted_uses:
  - summary: Resale or commercial use of purchases
    text: you are purchasing the Publisher Codes via the Services for your own exclusive and personal consumption
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To top-up or make a purchase using Codacash, you must (i) sign-up for a Coda Account with your email address or mobile phone number or by linking a supported social media platform account, and (ii) verify your identity using your email address or mobile phone number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coda Payments
provenance_date: '2026-11-09'
provider_name: Coda Payments
provider_slug: coda-payments
slug: coda-payments-eligibility
source_date: '2026-11-09'
source_filename: coda-payments-eligibility.yml
source_heading: Eligibility
source_page: https://www.coda.co/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coda Payments\naid: coda-payments\nurl: https://www.coda.co/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Codacash is available only to residents of listed Codacash Territories: Indonesia, Korea, Turkey, Thailand,\n    Brazil, Malaysia, Philippines.'\nentity_types: []\nrestricted_uses:\n- summary: Resale or commercial use of purchases\n  text: you are purchasing the Publisher Codes via the Services for your own exclusive and personal consumption\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To top-up or make a\
  \ purchase using Codacash, you must (i) sign-up for a Coda Account with your email address\n    or mobile phone number or by linking a supported social media platform account, and (ii) verify your identity\n    using your email address or mobile phone number.\nminimum_age:\n  value: age of majority in your country\n  text: The Services are not directed to persons under the age of majority in your country (a “minor” ).\n"
source_yaml_url: https://artifacts.apis.io/coda-payments/eligibility/coda-payments-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Coda Payments's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Merchant of Record
- Gaming
- Digital Goods
- Carrier Billing
- Digital Wallet
- Payouts
- Southeast Asia
- Monetization
---
