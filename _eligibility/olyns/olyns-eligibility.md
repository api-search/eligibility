---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must ... reside in the United States or a U.S. territory
  entity_types:
  - text: You must be at least 18 years old, reside in the United States or a U.S. territory, and be legally capable of entering a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Lawful personal purposes only
    text: license to access and use the Service for lawful personal purposes
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Olyns may require identity, account, device, payment-destination, or eligibility verification before permitting deposits, withdrawals, or other activity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Olyns
provenance_date: '2026-11-10'
provider_name: Olyns
provider_slug: olyns
slug: olyns-eligibility
source_date: '2026-11-10'
source_filename: olyns-eligibility.yml
source_heading: Eligibility
source_page: https://olyns.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Olyns\naid: olyns\nurl: https://olyns.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must ... reside in the United States or a U.S. territory\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, reside in the United States or a U.S. territory, and be legally capable\n    of entering a binding contract.\nrestricted_uses:\n- summary: Lawful personal purposes only\n  text: license to access and use the Service for lawful personal purposes\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Olyns may require\
  \ identity, account, device, payment-destination, or eligibility verification before permitting\n    deposits, withdrawals, or other activity.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/olyns/eligibility/olyns-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Olyns's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recycling
- Sustainability
- Circular Economy
- Retail Media
- Digital Out Of Home
- Advertising
- Artificial Intelligence
- Reverse Vending
- Consumer
---
