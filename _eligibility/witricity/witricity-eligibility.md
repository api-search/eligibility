---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a US Government embargo, or that has been designated by the US Government as a “terrorist supporting” country
  entity_types:
  - text: The Site and the Services are intended for use by individuals who are at least the age of majority in their jurisdiction of residence.
    type: individual
  minimum_age:
    text: The Site and the Services are intended for use by individuals who are at least the age of majority in their jurisdiction of residence.
    value: age of majority
  restricted_uses:
  - summary: Access from territories where content is illegal
    text: Accessing the Site or the Services from territories where the content is illegal is expressly prohibited.
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
name: WiTricity
provenance_date: '2026-11-10'
provider_name: WiTricity
provider_slug: witricity
slug: witricity-eligibility
source_date: '2026-11-10'
source_filename: witricity-eligibility.yml
source_heading: Eligibility
source_page: https://www.witricity.com/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WiTricity\naid: witricity\nurl: https://www.witricity.com/terms.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a US Government embargo, or that has been designated\n    by the US Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: The Site and the Services are intended for use by individuals who are at least the age of majority in their\n    jurisdiction of residence.\nrestricted_uses:\n- summary: Access from territories where content is illegal\n  text: Accessing the Site or the Services\
  \ from territories where the content is illegal is expressly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: The Site and the Services are intended for use by individuals who are at least the age of majority in their\n    jurisdiction of residence.\n"
source_yaml_url: https://artifacts.apis.io/witricity/eligibility/witricity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WiTricity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wireless Power
- Electric Vehicles
- EV Charging
- Automotive
- Energy
- Hardware
- Intellectual Property Licensing
- Smart Cities
- Vehicle-to-Grid
---
