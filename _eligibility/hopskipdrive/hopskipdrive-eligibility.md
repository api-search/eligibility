---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years of age and have the right, authority, and capacity to enter into and abide by the terms and conditions of these Terms.
    type: individual
  - text: Ride Organizers include schools, districts, nonprofits and government entities (“Enterprise Customers”)
    type: other
  minimum_age:
    text: You must be at least eighteen (18) years of age and have the right, authority, and capacity to enter into and abide by the terms and conditions of these Terms. In addition, you must be at least twenty-one (21) years of age to use the Platform to provide Services as a CareDriver.
    value: '18'
  restricted_uses:
  - summary: Safety of persons
    text: Jeopardizes the safety of any person or causes any harm or injury to any person, including by violating the Community Guidelines
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
name: HopSkipDrive
provenance_date: '2026-11-09'
provider_name: HopSkipDrive
provider_slug: hopskipdrive
slug: hopskipdrive-eligibility
source_date: '2026-11-09'
source_filename: hopskipdrive-eligibility.yml
source_heading: Eligibility
source_page: https://www.hopskipdrive.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HopSkipDrive\naid: hopskipdrive\nurl: https://www.hopskipdrive.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age and have the right, authority, and capacity to enter into\n    and abide by the terms and conditions of these Terms.\n- type: other\n  text: Ride Organizers include schools, districts, nonprofits and government entities (“Enterprise Customers”)\nrestricted_uses:\n- summary: Safety of persons\n  text: Jeopardizes the safety of any person or\
  \ causes any harm or injury to any person, including by violating\n    the Community Guidelines\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age and have the right, authority, and capacity to enter into\n    and abide by the terms and conditions of these Terms. In addition, you must be at least twenty-one (21) years\n    of age to use the Platform to provide Services as a CareDriver.\n"
source_yaml_url: https://artifacts.apis.io/hopskipdrive/eligibility/hopskipdrive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from HopSkipDrive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Student Transportation
- Education
- Mobility
- Ride Hailing
- School Districts
- Logistics
- Routing
- Government
---
