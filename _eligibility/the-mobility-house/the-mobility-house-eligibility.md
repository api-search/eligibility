---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Companies as defined by these Terms are natural persons or legal partnerships with whom business relations are established and who are pursuing commercial or independent professional activities, as well as legal entities under public law.
    type: business
  - text: Consumers as defined by these Terms are natural persons with whom business relations are established without this involving commercial or independent professional activity.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: The Mobility House
provenance_date: '2026-11-10'
provider_name: The Mobility House
provider_slug: the-mobility-house
slug: the-mobility-house-eligibility
source_date: '2026-11-10'
source_filename: the-mobility-house-eligibility.yml
source_heading: Eligibility
source_page: https://www.mobilityhouse.com/int_en/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Mobility House\naid: the-mobility-house\nurl: https://www.mobilityhouse.com/int_en/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Companies as defined by these Terms are natural persons or legal partnerships with whom business relations\n    are established and who are pursuing commercial or independent professional activities, as well as legal entities\n    under public law.\n- type: individual\n  text: Consumers as defined by these Terms are natural persons with whom business relations are established without\n\
  \    this involving commercial or independent professional activity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/the-mobility-house/eligibility/the-mobility-house-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from The Mobility House's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Electric Vehicles
- EV Charging
- Smart Charging
- Energy Management
- Vehicle-to-Grid
- Load Management
- Fleet Management
- OCPP
- VDV 463
- Modbus
- Germany
---
