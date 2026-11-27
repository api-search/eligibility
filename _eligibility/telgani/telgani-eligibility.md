---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any person can open an account on the Telgani website/application, acknowledging that they are over 21 years old.
    type: individual
  minimum_age:
    text: Drivers must be at least 21 years old.
    value: '21'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may need to wait for the rental company to verify the renter's eligibility; in this case, we will inform you accordingly.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Telgani
provenance_date: '2026-11-10'
provider_name: Telgani
provider_slug: telgani
slug: telgani-eligibility
source_date: '2026-11-10'
source_filename: telgani-eligibility.yml
source_heading: Eligibility
source_page: https://www.telgani.com/en/terms#definition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Telgani\naid: telgani\nurl: https://www.telgani.com/en/terms#definition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any person can open an account on the Telgani website/application, acknowledging that they are over 21 years\n    old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may need to wait for the rental company to verify the renter's eligibility; in this case, we will inform\n    you accordingly.\nminimum_age:\n  value: '21'\n  text: Drivers must be at least 21 years\
  \ old.\n"
source_yaml_url: https://artifacts.apis.io/telgani/eligibility/telgani-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Telgani's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Car Rental
- Mobility
- Marketplace
- Travel
- Transportation
- Saudi Arabia
- Consumer App
---
