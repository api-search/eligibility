---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Creating a Chipotle account is open to legal residents of the 50 United States of America and Washington, D.C. who are 13 years of age or older.
  entity_types:
  - text: Chipotle accounts are intended for personal use only.
    type: individual
  - text: Commercial use is prohibited.
    type: business
  minimum_age:
    text: who are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Commercial use
    text: Commercial use is prohibited.
  - summary: Tester plaintiff or claimant access
    text: The Services are not intended to be accessed by any person who seeks or intends to access the Services for purposes of being a “tester” plaintiff or claimant
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
name: Chipotle Mexican Grill
provenance_date: '2026-11-09'
provider_name: Chipotle Mexican Grill
provider_slug: chipotle-mexican-grill
slug: chipotle-mexican-grill-eligibility
source_date: '2026-11-09'
source_filename: chipotle-mexican-grill-eligibility.yml
source_heading: Eligibility
source_page: https://www.chipotle.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chipotle Mexican Grill\naid: chipotle-mexican-grill\nurl: https://www.chipotle.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Creating a Chipotle account is open to legal residents of the 50 United States of America and Washington,\n    D.C. who are 13 years of age or older.\nentity_types:\n- type: individual\n  text: Chipotle accounts are intended for personal use only.\n- type: business\n  text: Commercial use is prohibited.\nrestricted_uses:\n- summary: Commercial use\n  text: Commercial use is prohibited.\n- summary: Tester plaintiff or claimant access\n\
  \  text: The Services are not intended to be accessed by any person who seeks or intends to access the Services for\n    purposes of being a “tester” plaintiff or claimant\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: who are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/chipotle-mexican-grill/eligibility/chipotle-mexican-grill-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Chipotle Mexican Grill's own page on 2026-11-09.
synthetic: false
tags:
- Burritos
- Catering
- Digital Ordering
- Fast Casual
- Food Safety
- Fortune 500
- Loyalty
- Mobile App
- Quick Service Restaurant
- Restaurant Technology
- Restaurant
- Rewards
---
