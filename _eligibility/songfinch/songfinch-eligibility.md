---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is controlled and offered by Songfinch from its facilities in the United States of America. Songfinch makes no representations that the Website is appropriate or available for use in other locations.
  entity_types:
  - text: By accessing the Website, you represent that you are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: No commercial solicitation via Website communications
    text: nor use the communication systems provided by the Website for any commercial solicitation purposes
  - summary: Customer Referral Program personal use only
    text: The Customer Referral Program cannot be used for any commercial purpose.
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
name: Songfinch
provenance_date: '2026-11-10'
provider_name: Songfinch
provider_slug: songfinch
slug: songfinch-eligibility
source_date: '2026-11-10'
source_filename: songfinch-eligibility.yml
source_heading: Eligibility
source_page: https://www.songfinch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Songfinch\naid: songfinch\nurl: https://www.songfinch.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is controlled and offered by Songfinch from its facilities in the United States of America.\n    Songfinch makes no representations that the Website is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: By accessing the Website, you represent that you are of legal age to form a binding contract\nrestricted_uses:\n- summary: No commercial solicitation via Website communications\n  text: nor use the communication systems\
  \ provided by the Website for any commercial solicitation purposes\n- summary: Customer Referral Program personal use only\n  text: The Customer Referral Program cannot be used for any commercial purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental\n    or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/songfinch/eligibility/songfinch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Songfinch's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Marketplace
- E-Commerce
- Gifting
- Consumer
- Entertainment
- Creator Economy
- Personalization
---
