---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Misuse of the Site
    text: you will not use the Site for any illegal or un-authorized purpose
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
name: Hyperguest
provenance_date: '2026-11-09'
provider_name: Hyperguest
provider_slug: hyperguest
slug: hyperguest-eligibility
source_date: '2026-11-09'
source_filename: hyperguest-eligibility.yml
source_heading: Eligibility
source_page: https://www.hyperguest.com/user-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hyperguest\naid: hyperguest\nurl: https://www.hyperguest.com/user-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Misuse of the Site\n  text: you will not use the Site for any illegal or un-authorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/hyperguest/eligibility/hyperguest-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hyperguest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hospitality
- Hotels
- Travel
- Distribution
- Connectivity
- Booking
- Payments
---
