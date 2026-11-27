---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Products are not offered or intended for sale outside of the United States and Canada.
  entity_types:
  - text: all purchases through the Site are for end-users only and for personal and non-commercial use of the Products.
    type: individual
  - text: For any non-personal or commercial use of any Products, you must acquire an Omni One Enterprise license.
    type: business
  minimum_age:
    text: The Products are intended solely for users who are aged 13 years or older.
    value: '13'
  restricted_uses:
  - summary: Commercial use
    text: Unless you purchase an Omni One Enterprise system, all purchases through the Site are for end-users only and for personal and non-commercial use of the Products.
  - summary: Users under 13
    text: The Products are intended solely for users who are aged 13 years or older.
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
name: Virtuix
provenance_date: '2026-11-10'
provider_name: Virtuix
provider_slug: virtuix
slug: virtuix-eligibility
source_date: '2026-11-10'
source_filename: virtuix-eligibility.yml
source_heading: Eligibility
source_page: https://virtuix.com/terms-of-sale
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virtuix\naid: virtuix\nurl: https://virtuix.com/terms-of-sale\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Products are not offered or intended for sale outside of the United States and Canada.\nentity_types:\n- type: individual\n  text: all purchases through the Site are for end-users only and for personal and non-commercial use of the Products.\n- type: business\n  text: For any non-personal or commercial use of any Products, you must acquire an Omni One Enterprise license.\nrestricted_uses:\n- summary: Commercial use\n  text: Unless you purchase an Omni One\
  \ Enterprise system, all purchases through the Site are for end-users only\n    and for personal and non-commercial use of the Products.\n- summary: Users under 13\n  text: The Products are intended solely for users who are aged 13 years or older.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Products are intended solely for users who are aged 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/virtuix/eligibility/virtuix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Virtuix's own page on 2026-11-10.
synthetic: false
tags:
- Virtual Reality
- Gaming
- Hardware
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- Esports
- Game Development
- Location-Based Entertainment
- Consumer Electronics
---
