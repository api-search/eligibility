---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fuel tax reporting accuracy
    text: If you use our product for fuel tax reporting, you are liable for the accuracy of the data you submit to any government entity.
  - summary: Dependent person monitoring
    text: Devices and Services are not substitutes for management, care, or any other form of monitoring for a dependent person who may need constant supervision and should not be used as such.
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
name: FleetSharp
provenance_date: '2026-11-09'
provider_name: FleetSharp
provider_slug: fleetsharp
slug: fleetsharp-eligibility
source_date: '2026-11-09'
source_filename: fleetsharp-eligibility.yml
source_heading: Eligibility
source_page: https://www.fleetsharp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FleetSharp\naid: fleetsharp\nurl: https://www.fleetsharp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fuel tax reporting accuracy\n  text: If you use our product for fuel tax reporting, you are liable for the accuracy of the data you submit to\n    any government entity.\n- summary: Dependent person monitoring\n  text: Devices and Services are not substitutes for management, care, or any other form of monitoring for a dependent\n    person who may need constant supervision and should not be used as such.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fleetsharp/eligibility/fleetsharp-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from FleetSharp's own page on 2026-11-09.
synthetic: false
tags:
- GPS
- Fleet Tracking
- Asset Management
- Dash Cameras
- Software
---
