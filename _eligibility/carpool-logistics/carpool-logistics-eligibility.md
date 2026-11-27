---
claim_count: 1
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
  - summary: Prohibited items in shipments
    text: Customer understands and accepts that Customer is expressly prohibited from loading any explosives, guns, ammunition, weapons, flammable products, live pets, live plants, any contraband, drugs or narcotics, alcoholic beverages, and or any illegal goods in the Shipment.
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
name: Carpool Logistics
provenance_date: '2026-11-09'
provider_name: Carpool Logistics
provider_slug: carpool-logistics
slug: carpool-logistics-eligibility
source_date: '2026-11-09'
source_filename: carpool-logistics-eligibility.yml
source_heading: Eligibility
source_page: https://www.carpoollogistics.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carpool Logistics\naid: carpool-logistics\nurl: https://www.carpoollogistics.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited items in shipments\n  text: Customer understands and accepts that Customer is expressly prohibited from loading any explosives, guns,\n    ammunition, weapons, flammable products, live pets, live plants, any contraband, drugs or narcotics, alcoholic\n    beverages, and or any illegal goods in the Shipment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carpool-logistics/eligibility/carpool-logistics-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Carpool Logistics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Vehicles
- Transportation
- Supply Chain
---
