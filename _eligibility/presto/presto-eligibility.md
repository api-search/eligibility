---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and operated from facilities in the United States. You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-compatible vehicles
    text: Chargers in the Presto network are intended for use solely for standard, unmodified, industry-manufactured automotive land vehicles. Using Presto for the charging of any other type of vehicle, including home-built electric vehicles, home-built onboard chargers, and vehicles that contain personally modified chargers, is prohibited.
  - summary: Users previously removed
    text: The Service is not available to Users previously removed from the Service by Presto.
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
name: Presto
provenance_date: '2026-11-10'
provider_name: Presto
provider_slug: presto
slug: presto-eligibility
source_date: '2026-11-10'
source_filename: presto-eligibility.yml
source_heading: Eligibility
source_page: https://www.prestocharging.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Presto\naid: presto\nurl: https://www.prestocharging.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and operated from facilities in the United States. You may not use the Service\n    if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked\n    or denied by the United States government.\nentity_types: []\nrestricted_uses:\n- summary: Non-compatible vehicles\n  text: Chargers in the Presto network are intended for use solely for standard, unmodified, industry-manufactured\n    automotive\
  \ land vehicles. Using Presto for the charging of any other type of vehicle, including home-built electric\n    vehicles, home-built onboard chargers, and vehicles that contain personally modified chargers, is prohibited.\n- summary: Users previously removed\n  text: The Service is not available to Users previously removed from the Service by Presto.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/presto/eligibility/presto-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Presto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EV Charging
- Electric Vehicles
- Mobility
- Charging Networks
- Fleet Management
- OCPI
- Payments
- White Label
---
