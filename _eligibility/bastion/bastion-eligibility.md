---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is operated by us in the United States. Those who choose to access the Website from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: If you use the Website on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Website.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: personal non-commercial use only
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
name: Bastion
provenance_date: '2026-11-09'
provider_name: Bastion
provider_slug: bastion
slug: bastion-eligibility
source_date: '2026-11-09'
source_filename: bastion-eligibility.yml
source_heading: Eligibility
source_page: https://support.bastion.com/hc/en-us/articles/53792145590036-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bastion\naid: bastion\nurl: https://support.bastion.com/hc/en-us/articles/53792145590036-Terms-of-Service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is operated by us in the United States. Those who choose to access the Website from locations\n    outside the United States do so at their own initiative and are responsible for compliance with applicable local\n    laws.\nentity_types:\n- type: business\n  text: If you use the Website on behalf of a company or other entity then “you” includes you and that entity, and\n    you represent and warrant that (a) you are\
  \ an authorized representative of the entity\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: personal non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/bastion/eligibility/bastion-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bastion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Stablecoins
- Payments
- Wallets
- Custody
- Web3
- Compliance
- Crypto Infrastructure
- Financial Services
- On/Off-Ramps
- Stablecoin Issuance
---
