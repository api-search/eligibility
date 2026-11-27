---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Suspicious activity
    text: If Provable Markets LLC determines that Client is engaging in, or has engaged in, any suspicious activity, Provable Markets LLC reserves the right to terminate Client’s access
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
name: Provable
provenance_date: '2026-11-10'
provider_name: Provable
provider_slug: provable
slug: provable-eligibility
source_date: '2026-11-10'
source_filename: provable-eligibility.yml
source_heading: Eligibility
source_page: https://provablemarkets.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Provable\naid: provable\nurl: https://provablemarkets.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Suspicious activity\n  text: If Provable Markets LLC determines that Client is engaging in, or has engaged in, any suspicious activity,\n    Provable Markets LLC reserves the right to terminate Client’s access\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/provable/eligibility/provable-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Provable's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Securities Lending
- Capital Markets
- Fintech
- Trading
- Alternative Trading System
- Post-Trade
- gRPC
- FIX
---
