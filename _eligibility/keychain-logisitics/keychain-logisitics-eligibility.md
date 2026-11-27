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
  - summary: Prohibited AI Feature uses
    text: generate or distribute spam, unsolicited commercial emails, or deceptive marketing materials
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
name: Keychain
provenance_date: '2026-11-09'
provider_name: Keychain
provider_slug: keychain-logisitics
slug: keychain-logisitics-eligibility
source_date: '2026-11-09'
source_filename: keychain-logisitics-eligibility.yml
source_heading: Eligibility
source_page: https://www.keychain.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keychain\naid: keychain-logisitics\nurl: https://www.keychain.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited AI Feature uses\n  text: generate or distribute spam, unsolicited commercial emails, or deceptive marketing materials\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/keychain-logisitics/eligibility/keychain-logisitics-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Keychain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Manufacturing
- Contract Manufacturing
- Supply Chain
- Marketplace
- Artificial Intelligence
---
