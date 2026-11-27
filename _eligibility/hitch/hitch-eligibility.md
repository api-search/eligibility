---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You possess a valid driver's license issued by one of the 50 states in the U.S.A.
  entity_types:
  - text: '"Rider" means a non-driving human user who uses the Platform to discover, identify, request, order, purchase, schedule or participate in Rides provided by Drivers.'
    type: individual
  - text: All Drivers who use the Platform to offer and arrange for Rides and other Driver Services are independent service providers who provide Driver Services directly to Riders.
    type: other
  minimum_age:
    text: we do not accept responsibility or liability for any Content, communication or other use or access of the Platform by persons under the age of 18 in violation of this Agreement.
    value: null
  restricted_uses:
  - summary: Commercial use
    text: use the Platform for any commercial uses without our express written approval
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: we review the application of Driver Applicants and, if accepted to be a Driver, we conduct an Onboarding process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hitch
provenance_date: '2026-11-09'
provider_name: Hitch
provider_slug: hitch
slug: hitch-eligibility
source_date: '2026-11-09'
source_filename: hitch-eligibility.yml
source_heading: Eligibility
source_page: https://www.hitch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hitch\naid: hitch\nurl: https://www.hitch.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You possess a valid driver's license issued by one of the 50 states in the U.S.A.\nentity_types:\n- type: individual\n  text: '\"Rider\" means a non-driving human user who uses the Platform to discover, identify, request, order, purchase,\n    schedule or participate in Rides provided by Drivers.'\n- type: other\n  text: All Drivers who use the Platform to offer and arrange for Rides and other Driver Services are independent\n    service providers who provide\
  \ Driver Services directly to Riders.\nrestricted_uses:\n- summary: Commercial use\n  text: use the Platform for any commercial uses without our express written approval\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: we review the application of Driver Applicants and, if accepted to be a Driver, we conduct an Onboarding\n    process\nminimum_age:\n  value: null\n  text: we do not accept responsibility or liability for any Content, communication or other use or access of the\n    Platform by persons under the age of 18 in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/hitch/eligibility/hitch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Hitch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ride Hailing
- Transportation
- Mobile App
- LongDistance
---
