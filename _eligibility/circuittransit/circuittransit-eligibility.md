---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Circuit makes no representation that the Website is appropriate or available in other locations other than where it is operated by Circuit.
  entity_types:
  - text: You must be at least sixteen (16) years of age to register for an Account and to use the Services.
    type: individual
  - text: whether personally or on behalf of an entity (“user” or “you”)
    type: business
  minimum_age:
    text: You must be at least sixteen (16) years of age to register for an Account and to use the Services.
    value: '16'
  restricted_uses:
  - summary: Unlawful or hazardous transport
    text: you may only access or use the Services for lawful purposes (e.g., no transport of unlawful or hazardous materials)
  - summary: Commercial use without permission
    text: Unless otherwise agreed by Circuit in a separate written agreement with you, the Services are made available solely for your personal, noncommercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be asked to provide proof of identity or other methods of identity verification to access or use the Services, and you agree that you may be denied access to or use of the Services if you refuse to provide proof of identity or other methods of identity verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Circuittransit
provenance_date: '2026-11-09'
provider_name: Circuittransit
provider_slug: circuittransit
slug: circuittransit-eligibility
source_date: '2026-11-09'
source_filename: circuittransit-eligibility.yml
source_heading: Eligibility
source_page: https://www.ridecircuit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Circuittransit\naid: circuittransit\nurl: https://www.ridecircuit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Circuit makes no representation that the Website is appropriate or available in other locations other than\n    where it is operated by Circuit.\nentity_types:\n- type: individual\n  text: You must be at least sixteen (16) years of age to register for an Account and to use the Services.\n- type: business\n  text: whether personally or on behalf of an entity (“user” or “you”)\nrestricted_uses:\n- summary: Unlawful or hazardous transport\n  text: you may only\
  \ access or use the Services for lawful purposes (e.g., no transport of unlawful or hazardous\n    materials)\n- summary: Commercial use without permission\n  text: Unless otherwise agreed by Circuit in a separate written agreement with you, the Services are made available\n    solely for your personal, noncommercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be asked to provide proof of identity or other methods of identity verification to access or use\n    the Services, and you agree that you may be denied access to or use of the Services if you refuse to provide\n    proof of identity or other methods of identity verification.\nminimum_age:\n  value: '16'\n  text: You must be at least sixteen (16) years of age to register for an Account and to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/circuittransit/eligibility/circuittransit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Circuittransit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Electric Vehicles
- On-demand Mobility
- Software-as-a-Service
---
