---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The 'Client' is any individual or entity registered with FYERS having a valid UCC (Unique Client Code) account approved by the Exchanges and Depositories.
    type: individual
  - text: Entities shall include, as the case may be, body corporates, 'Partnerships' under the Indian Partnership Act, 1932, 'Companies' under the 'Companies Act 1956' or the 'Companies Act 2013', where applicable.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Proprietary trading only
    text: We hereby inform that we engage exclusively in proprietary trading. All trades are executed solely with our own capital, and no client funds are used or involved at any stage of our operations.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: The client agrees to give absolute consent to FYERS to fetch the KYC data and other documents required for account opening from KRA/Digi Locker during the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fyers
provenance_date: '2026-11-09'
provider_name: Fyers
provider_slug: fyers
slug: fyers-eligibility
source_date: '2026-11-09'
source_filename: fyers-eligibility.yml
source_heading: Eligibility
source_page: https://fyers.in/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fyers\naid: fyers\nurl: https://fyers.in/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The 'Client' is any individual or entity registered with FYERS having a valid UCC (Unique Client Code) account\n    approved by the Exchanges and Depositories.\n- type: business\n  text: Entities shall include, as the case may be, body corporates, 'Partnerships' under the Indian Partnership\n    Act, 1932, 'Companies' under the 'Companies Act 1956' or the 'Companies Act 2013', where applicable.\nrestricted_uses:\n- summary:\
  \ Proprietary trading only\n  text: We hereby inform that we engage exclusively in proprietary trading. All trades are executed solely with\n    our own capital, and no client funds are used or involved at any stage of our operations.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: The client agrees to give absolute consent to FYERS to fetch the KYC data and other documents required for\n    account opening from KRA/Digi Locker during the signup process.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fyers/eligibility/fyers-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Fyers's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trading
- Brokerage
- Fintech
---
