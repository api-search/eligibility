---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: regardless of your location and/or nationality
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illicit-address transactions
    text: Pintu may undertake necessary measures, including but not limited to freeze your Account, decline, and/ or suspend Transactions from your Account
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Pintu may be required to establish and verify your identity, or the identity of any relevant beneficial owner pursuant to applicable laws, regulations, notices and guidelines.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pintu
provenance_date: '2026-11-10'
provider_name: Pintu
provider_slug: pintu
slug: pintu-eligibility
source_date: '2026-11-10'
source_filename: pintu-eligibility.yml
source_heading: Eligibility
source_page: https://pintu.co.id/en/pages/pintu-pro-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pintu\naid: pintu\nurl: https://pintu.co.id/en/pages/pintu-pro-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: regardless of your location and/or nationality\nentity_types: []\nrestricted_uses:\n- summary: Illicit-address transactions\n  text: Pintu may undertake necessary measures, including but not limited to freeze your Account, decline, and/\n    or suspend Transactions from your Account\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Pintu may be required to establish and verify your identity, or the identity of any relevant\
  \ beneficial\n    owner pursuant to applicable laws, regulations, notices and guidelines.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pintu/eligibility/pintu-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Pintu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Cryptocurrency Exchange
- Trading
- Fintech
- Digital Assets
- Web3
- Indonesia
- WebSocket
- Institutional Trading
---
