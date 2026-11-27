---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Service is void where prohibited; materials are not intended for distribution where contrary to law.
  entity_types:
  - text: You represent that (1) you are age 13 or older, (2) you understand and agree to these Terms of Service, and (3) if you are between the ages of 13 and 18, your legal guardian has reviewed and agrees to these Terms of Service.
    type: individual
  minimum_age:
    text: You shall not create an Account or access the Service if you are under the age of 13
    value: '13'
  restricted_uses:
  - summary: No commercial use of account
    text: You shall not use your Account for any commercial purpose, including without limitation, (a) any attempt to raise money for any party or any purpose or advertise
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
name: Pocket Gems
provenance_date: '2026-11-10'
provider_name: Pocket Gems
provider_slug: pocket-gems
slug: pocket-gems-eligibility
source_date: '2026-11-10'
source_filename: pocket-gems-eligibility.yml
source_heading: Eligibility
source_page: https://www.pocketgems.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pocket Gems\naid: pocket-gems\nurl: https://www.pocketgems.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Service is void where prohibited; materials are not intended for distribution where contrary\n    to law.\nentity_types:\n- type: individual\n  text: You represent that (1) you are age 13 or older, (2) you understand and agree to these Terms of Service,\n    and (3) if you are between the ages of 13 and 18, your legal guardian has reviewed and agrees to these Terms\n    of Service.\nrestricted_uses:\n- summary: No commercial use of account\n\
  \  text: You shall not use your Account for any commercial purpose, including without limitation, (a) any attempt\n    to raise money for any party or any purpose or advertise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You shall not create an Account or access the Service if you are under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/pocket-gems/eligibility/pocket-gems-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pocket Gems's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Mobile Games
- Interactive Fiction
- Entertainment
- Mobile App
- Game Development
- Consumer Software
---
