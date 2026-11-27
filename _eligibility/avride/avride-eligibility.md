---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Passengers under the age of 18 are not permitted in the Vehicle unless they are accompanied by you or otherwise authorized by AVRIDE.
    value: '18'
  restricted_uses:
  - summary: Emergency or mission-critical use
    text: The Services are not intended for use in emergency situations or for time-sensitive or mission-critical transportation needs.
  - summary: Commercial purpose
    text: use the Services for a commercial purpose
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
name: Avride
provenance_date: '2026-11-09'
provider_name: Avride
provider_slug: avride
slug: avride-eligibility
source_date: '2026-11-09'
source_filename: avride-eligibility.yml
source_heading: Eligibility
source_page: https://www.avride.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avride\naid: avride\nurl: https://www.avride.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Emergency or mission-critical use\n  text: The Services are not intended for use in emergency situations or for time-sensitive or mission-critical\n    transportation needs.\n- summary: Commercial purpose\n  text: use the Services for a commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Passengers under the age of 18 are not permitted in the\
  \ Vehicle unless they are accompanied by you or otherwise\n    authorized by AVRIDE.\n"
source_yaml_url: https://artifacts.apis.io/avride/eligibility/avride-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Avride's own page on 2026-11-09.
synthetic: false
tags:
- Autonomous Vehicles
- Delivery Robots
- Artificial Intelligence
- Mobility
- Technology
---
