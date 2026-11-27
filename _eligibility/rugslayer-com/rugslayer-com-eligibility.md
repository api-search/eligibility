---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Don’t use RugSlayer where using it, or trading crypto assets, is illegal for you, or if U.S. sanctions bar you from using U.S. services.
  entity_types:
  - text: You must be at least 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal use or sanctions-barred users
    text: Don’t use RugSlayer where using it, or trading crypto assets, is illegal for you, or if U.S. sanctions bar you from using U.S. services.
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
name: rugslayer-com
provenance_date: '2026-11-10'
provider_name: rugslayer-com
provider_slug: rugslayer-com
slug: rugslayer-com-eligibility
source_date: '2026-11-10'
source_filename: rugslayer-com-eligibility.yml
source_heading: Eligibility
source_page: https://rugslayer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rugslayer-com\naid: rugslayer-com\nurl: https://rugslayer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Don’t use RugSlayer where using it, or trading crypto assets, is illegal for you, or if U.S. sanctions bar\n    you from using U.S. services.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old.\nrestricted_uses:\n- summary: Illegal use or sanctions-barred users\n  text: Don’t use RugSlayer where using it, or trading crypto assets, is illegal for you, or if U.S. sanctions bar\n    you from using U.S. services.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/rugslayer-com/eligibility/rugslayer-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from rugslayer-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Solana
- Security
- Cryptocurrency
- Risk-Scanner
---
