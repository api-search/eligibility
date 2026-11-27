---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - IR
    - CU
    - KP
    - SD
    - SY
    served: []
    text: 'Customer represents and warrants that it is not: (a) a resident of any country subject to a United States embargo or other similar United States export restrictions, including Iran, Cuba, North Korea, the Region of Crimea, Sudan or Syria'
  entity_types:
  - text: Customer’s representative entering into this Agreement must be at least 18 years old
    type: individual
  minimum_age:
    text: must be at least 18 years old (or the age of legal majority in his or her state of residence) to purchase, access or use the Airwise Solutions
    value: '18'
  restricted_uses:
  - summary: Safety-critical and manned aviation systems
    text: The Services are not intended for use in, and you may not use the Services for, the operation of manned aircraft navigation or communication systems, air traffic control systems, life support machines
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- CU
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AirWise Solutions
provenance_date: '2026-11-09'
provider_name: AirWise Solutions
provider_slug: airwise-solutions
slug: airwise-solutions-eligibility
source_date: '2026-11-09'
source_filename: airwise-solutions-eligibility.yml
source_heading: Eligibility
source_page: https://airwisesolutions.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AirWise Solutions\naid: airwise-solutions\nurl: https://airwisesolutions.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - CU\n  - KP\n  - SD\n  - SY\n  text: 'Customer represents and warrants that it is not: (a) a resident of any country subject to a United States\n    embargo or other similar United States export restrictions, including Iran, Cuba, North Korea, the Region of\n    Crimea, Sudan or Syria'\nentity_types:\n- type: individual\n  text: Customer’s representative entering into this Agreement must be at least 18 years old\nrestricted_uses:\n- summary:\
  \ Safety-critical and manned aviation systems\n  text: The Services are not intended for use in, and you may not use the Services for, the operation of manned\n    aircraft navigation or communication systems, air traffic control systems, life support machines\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: must be at least 18 years old (or the age of legal majority in his or her state of residence) to purchase,\n    access or use the Airwise Solutions\n"
source_yaml_url: https://artifacts.apis.io/airwise-solutions/eligibility/airwise-solutions-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AirWise Solutions's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Drones
- UAS
- Aviation
- Airspace
- UTM
- Public Safety
- Critical Infrastructure
- Geospatial
---
