---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All Services are performed, controlled, and operated from US-based facilities, and 1upHealth makes no representations that the Services are appropriate or available for use in other locations.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Abusive or unlawful use
    text: Use the Services, or any part thereof, for a purpose that is abusive, deceptive, or violates any Applicable Law
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
name: 1upHealth
provenance_date: '2026-11-09'
provider_name: 1upHealth
provider_slug: 1uphealth
slug: 1uphealth-eligibility
source_date: '2026-11-09'
source_filename: 1uphealth-eligibility.yml
source_heading: Eligibility
source_page: https://1up.health/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1upHealth\naid: 1uphealth\nurl: https://1up.health/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: All Services are performed, controlled, and operated from US-based facilities, and 1upHealth makes no representations\n    that the Services are appropriate or available for use in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Abusive or unlawful use\n  text: Use the Services, or any part thereof, for a purpose that is abusive, deceptive, or violates any Applicable\n    Law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/1uphealth/eligibility/1uphealth-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from 1upHealth's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- FHIR
- HL7
- Interoperability
- SMART on FHIR
- Payers
- Claims
- Patient Access
- Health Data
---
