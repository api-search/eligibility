---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Sites and the Services are intended for use only within the United States and its territories.
  entity_types:
  - text: In order to create an Account, you must be of the legal age to enter into a contract (i.e., be 18 in most states, or be an emancipated minor).
    type: individual
  minimum_age:
    text: you must be of the legal age to enter into a contract (i.e., be 18 in most states, or be an emancipated minor).
    value: '18'
  restricted_uses:
  - summary: Non-US residents outside US
    text: NON-UNITED STATES RESIDENTS MAY NOT USE THE SITES AND/OR THE SERVICES OUTSIDE OF THE UNITED STATES AND ITS TERRITORIES.
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
name: Tomorrow Health
provenance_date: '2026-11-10'
provider_name: Tomorrow Health
provider_slug: tomorrow-health
slug: tomorrow-health-eligibility
source_date: '2026-11-10'
source_filename: tomorrow-health-eligibility.yml
source_heading: Eligibility
source_page: https://9307612.fs1.hubspotusercontent-na1.net/hubfs/9307612/Website%20Files/Terms%20of%20Service%20.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tomorrow Health\naid: tomorrow-health\nurl: https://9307612.fs1.hubspotusercontent-na1.net/hubfs/9307612/Website%20Files/Terms%20of%20Service%20.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Sites and the Services are intended for use only within the United States and its territories.\nentity_types:\n- type: individual\n  text: In order to create an Account, you must be of the legal age to enter into a contract (i.e., be 18 in most\n    states, or be an emancipated minor).\nrestricted_uses:\n- summary: Non-US residents outside US\n  text: NON-UNITED STATES RESIDENTS\
  \ MAY NOT USE THE SITES AND/OR THE SERVICES OUTSIDE OF THE UNITED STATES AND ITS\n    TERRITORIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be of the legal age to enter into a contract (i.e., be 18 in most states, or be an emancipated\n    minor).\n"
source_yaml_url: https://artifacts.apis.io/tomorrow-health/eligibility/tomorrow-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tomorrow Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- DMEPOS
- DME
- Health Tech
- Care Coordination
- Health Insurance
---
