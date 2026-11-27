---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We control the Platform from within the United States. We make no representation that the Platform or Content are appropriate or available for use in other locations.
  entity_types:
  - text: The Platform is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for Services through the Platform.
    type: individual
  minimum_age:
    text: The Platform is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Card not available in some states
    text: The Nibbles Card is not currently available to residents of Colorado, Connecticut, Hawaii, New York, Puerto Rico, Maine, Massachusetts, Minnesota, or Washington.
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
name: Nibbles PBC
provenance_date: '2026-11-10'
provider_name: Nibbles PBC
provider_slug: nibbles-pbc
slug: nibbles-pbc-eligibility
source_date: '2026-11-10'
source_filename: nibbles-pbc-eligibility.yml
source_heading: Eligibility
source_page: https://nibbles.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nibbles PBC\naid: nibbles-pbc\nurl: https://nibbles.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We control the Platform from within the United States. We make no representation that the Platform or Content\n    are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: The Platform is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for Services through the Platform.\nrestricted_uses:\n- summary: Card not available in some states\n  text: The\
  \ Nibbles Card is not currently available to residents of Colorado, Connecticut, Hawaii, New York, Puerto\n    Rico, Maine, Massachusetts, Minnesota, or Washington.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Platform is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/nibbles-pbc/eligibility/nibbles-pbc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nibbles PBC's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pets
- Insurance
- Financial Services
- Credit Cards
- Consumer
- Public Benefit Company
- Rewards
- Finance
- Pet Care
- PBC
---
