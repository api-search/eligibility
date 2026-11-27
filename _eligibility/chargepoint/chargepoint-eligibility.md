---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You hereby represent and warrant that: (a) you are not located in a country that is subject to a U.S. Government embargo or that has been designated by the U.S. Government as a "terrorist supporting" country'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: Unless otherwise expressly authorized by ChargePoint in a separate written agreement, use the applicable Services only for personal, non-commercial purposes.
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
name: ChargePoint
provenance_date: '2026-11-09'
provider_name: ChargePoint
provider_slug: chargepoint
slug: chargepoint-eligibility
source_date: '2026-11-09'
source_filename: chargepoint-eligibility.yml
source_heading: Eligibility
source_page: https://na.chargepoint.com/terms_web
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChargePoint\naid: chargepoint\nurl: https://na.chargepoint.com/terms_web\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You hereby represent and warrant that: (a) you are not located in a country that is subject to a U.S. Government\n    embargo or that has been designated by the U.S. Government as a \"terrorist supporting\" country'\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Unless otherwise expressly authorized by ChargePoint in a separate written agreement, use the applicable\n    Services only for personal, non-commercial purposes.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chargepoint/eligibility/chargepoint-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from ChargePoint's own page on 2026-11-09.
synthetic: false
tags:
- EV Charging
- Electric Vehicles
- Fleet Management
- Energy Management
- Transportation
- Mobility
---
