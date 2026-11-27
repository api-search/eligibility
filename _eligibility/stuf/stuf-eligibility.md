---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is intended for use within the United States. Access outside the U.S. may not be legal, and users are responsible for compliance with local laws.
  entity_types:
  - text: The Website is intended for users who are 18 years of age or older and reside in the United States.
    type: individual
  minimum_age:
    text: The Website is intended for users who are 18 years of age or older and reside in the United States.
    value: '18'
  restricted_uses:
  - summary: Stuf Blue membership enrollment
    text: To enroll in Stuf Blue, you must be at least 18 years of age and have a valid email address.
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
name: Stuf Storage
provenance_date: '2026-11-10'
provider_name: Stuf Storage
provider_slug: stuf
slug: stuf-eligibility
source_date: '2026-11-10'
source_filename: stuf-eligibility.yml
source_heading: Eligibility
source_page: https://www.stufstorage.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stuf Storage\naid: stuf\nurl: https://www.stufstorage.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is intended for use within the United States. Access outside the U.S. may not be legal, and\n    users are responsible for compliance with local laws.\nentity_types:\n- type: individual\n  text: The Website is intended for users who are 18 years of age or older and reside in the United States.\nrestricted_uses:\n- summary: Stuf Blue membership enrollment\n  text: To enroll in Stuf Blue, you must be at least 18 years of age and have a valid email\
  \ address.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is intended for users who are 18 years of age or older and reside in the United States.\n"
source_yaml_url: https://artifacts.apis.io/stuf/eligibility/stuf-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Stuf Storage's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Self Storage
- Real Estate
- PropTech
- Logistics
- Consumer Marketplace
- Urban Infrastructure
- IoT
---
