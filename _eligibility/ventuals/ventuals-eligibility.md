---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - US
    - CA
    served: []
    text: 'Ventuals is not available to the following persons and entities: (a) persons or entities who reside in the United States of America, or Ontario, Canada'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned jurisdictions
    text: persons or entities (or any person owned or controlled by such persons or entities) who reside in jurisdictions subject to comprehensive economic and trade sanctions or export control laws and regulations, including the Crimea region, Cuba, Iran, North Korea, Syria, Myanmar (Burma), Donetsk, Luhansk
  - summary: Market manipulation and exploits
    text: engage in any activities designed to exploit vulnerabilities in the leverage or liquidation mechanisms of Ventuals
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- CA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ventuals
provenance_date: '2026-11-10'
provider_name: Ventuals
provider_slug: ventuals
slug: ventuals-eligibility
source_date: '2026-11-10'
source_filename: ventuals-eligibility.yml
source_heading: Eligibility
source_page: https://app.ventuals.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ventuals\naid: ventuals\nurl: https://app.ventuals.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CA\n  text: 'Ventuals is not available to the following persons and entities: (a) persons or entities who reside in\n    the United States of America, or Ontario, Canada'\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned jurisdictions\n  text: persons or entities (or any person owned or controlled by such persons or entities) who reside in jurisdictions\n    subject to comprehensive economic and trade sanctions or export control laws and regulations, including the\n\
  \    Crimea region, Cuba, Iran, North Korea, Syria, Myanmar (Burma), Donetsk, Luhansk\n- summary: Market manipulation and exploits\n  text: engage in any activities designed to exploit vulnerabilities in the leverage or liquidation mechanisms of\n    Ventuals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ventuals/eligibility/ventuals-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Ventuals's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Crypto Defi
- Perpetual Futures
- Pre-IPO
- Derivatives
- Trading
- Hyperliquid
---
