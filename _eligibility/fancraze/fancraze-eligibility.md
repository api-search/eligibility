---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE LEGAL AUTHORITY TO ACCEPT THESE TERMS ON THAT ENTITY’S BEHALF
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited activities
    text: YOU AGREE TO USE THE PLATFORM ONLY FOR PURPOSES THAT ARE LEGAL, PROPER AND IN ACCORDANCE WITH THESE TERMS AND ANY APPLICABLE LAWS OR REGULATIONS.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: completion of the KYC verification and identity check process is mandatory before your digital Account and Collectible Wallet can be created on the Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FanCraze
provenance_date: '2026-11-09'
provider_name: FanCraze
provider_slug: fancraze
slug: fancraze-eligibility
source_date: '2026-11-09'
source_filename: fancraze-eligibility.yml
source_heading: Eligibility
source_page: https://matchday.fancraze.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FanCraze\naid: fancraze\nurl: https://matchday.fancraze.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE\n    THE LEGAL AUTHORITY TO ACCEPT THESE TERMS ON THAT ENTITY’S BEHALF\nrestricted_uses:\n- summary: Prohibited activities\n  text: YOU AGREE TO USE THE PLATFORM ONLY FOR PURPOSES THAT ARE LEGAL, PROPER AND IN ACCORDANCE WITH THESE TERMS\n    AND ANY APPLICABLE LAWS OR REGULATIONS.\nverification:\n  kyc: true\n\
  \  kyb: null\n  approval_required: null\n  text: completion of the KYC verification and identity check process is mandatory before your digital Account and\n    Collectible Wallet can be created on the Platform.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fancraze/eligibility/fancraze-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from FanCraze's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Cricket
- Sports
- Collectibles
- Fantasy Sports
- Gaming
- Digital Collectibles
- Trading
---
