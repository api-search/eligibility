---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not use the Services unless you are (i) at least thirteen years old, (ii) the age of majority in the applicable jurisdiction
    type: individual
  minimum_age:
    text: at least thirteen years old
    value: '13'
  restricted_uses:
  - summary: Individual use only for location features
    text: The location-based services that may be offered in connection with the Services are for individual use only
  - summary: Life-critical reliance prohibited
    text: should not be used or relied on in any situation in which the failure or inaccuracy of use of the location-based services could lead to death, personal injury, or physical or property damage
  - summary: Export and sanctions restriction
    text: you are not located in a country that is subject to a United States Government embargo
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
name: Geocomply
provenance_date: '2026-11-09'
provider_name: Geocomply
provider_slug: geocomply
slug: geocomply-eligibility
source_date: '2026-11-09'
source_filename: geocomply-eligibility.yml
source_heading: Eligibility
source_page: https://www.geocomply.com/application-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Geocomply\naid: geocomply\nurl: https://www.geocomply.com/application-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not use the Services unless you are (i) at least thirteen years old, (ii) the age of majority in\n    the applicable jurisdiction\nrestricted_uses:\n- summary: Individual use only for location features\n  text: The location-based services that may be offered in connection with the Services are for individual use only\n- summary: Life-critical reliance prohibited\n  text: should\
  \ not be used or relied on in any situation in which the failure or inaccuracy of use of the location-based\n    services could lead to death, personal injury, or physical or property damage\n- summary: Export and sanctions restriction\n  text: you are not located in a country that is subject to a United States Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: at least thirteen years old\n"
source_yaml_url: https://artifacts.apis.io/geocomply/eligibility/geocomply-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Geocomply's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geolocation
- Compliance
- Fraud Prevention
- Identity Verification
- KYC
- iGaming
- Financial Services
- Security
---
