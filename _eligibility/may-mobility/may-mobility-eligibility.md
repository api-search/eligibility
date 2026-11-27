---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not create an Account or use another user's Account to access the Services if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: You may not create an Account or use another user's Account to access the Services if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: for your own non-commercial use
  - summary: Not for emergencies or mission-critical transport
    text: The Services are not intended for use in emergency situations or for time-sensitive or mission-critical transportation needs.
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
name: May Mobility
provenance_date: '2026-11-10'
provider_name: May Mobility
provider_slug: may-mobility
slug: may-mobility-eligibility
source_date: '2026-11-10'
source_filename: may-mobility-eligibility.yml
source_heading: Eligibility
source_page: https://maymobility.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: May Mobility\naid: may-mobility\nurl: https://maymobility.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not create an Account or use another user's Account to access the Services if you are not at least\n    18 years old.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: for your own non-commercial use\n- summary: Not for emergencies or mission-critical transport\n  text: The Services are not intended for use in emergency situations or for time-sensitive or mission-critical\n    transportation\
  \ needs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not create an Account or use another user's Account to access the Services if you are not at least\n    18 years old.\n"
source_yaml_url: https://artifacts.apis.io/may-mobility/eligibility/may-mobility-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from May Mobility's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Autonomous Vehicles
- Transportation
- Mobility
- Robotaxi
- Fleet Management
- Telemetry
- Public Transit
- Automotive
- Streaming
---
