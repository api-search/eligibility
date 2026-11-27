---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: within the United States and its territories and possessions and/or within Canada (excluding the Province of Québec)
  entity_types:
  - text: you are an individual (i.e., not a corporation or other legal entity)
    type: individual
  minimum_age:
    text: you are of legal age to form a binding contract in your jurisdiction (in some jurisdictions this is also referred to as the age of majority)
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: only for your own personal, non-commercial use
  - summary: No commercial activity without consent
    text: involves commercial activities or sales without Halo’s prior written consent such as contests, sweepstakes, barter, or advertising
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
name: Halo Collar
provenance_date: '2026-11-09'
provider_name: Halo Collar
provider_slug: halo-collar
slug: halo-collar-eligibility
source_date: '2026-11-09'
source_filename: halo-collar-eligibility.yml
source_heading: Eligibility
source_page: https://www.halocollar.com/unified-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halo Collar\naid: halo-collar\nurl: https://www.halocollar.com/unified-terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: within the United States and its territories and possessions and/or within Canada (excluding the Province\n    of Québec)\nentity_types:\n- type: individual\n  text: you are an individual (i.e., not a corporation or other legal entity)\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: only for your own personal, non-commercial use\n- summary: No commercial activity without consent\n  text:\
  \ involves commercial activities or sales without Halo’s prior written consent such as contests, sweepstakes,\n    barter, or advertising\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract in your jurisdiction (in some jurisdictions this is also\n    referred to as the age of majority)\n"
source_yaml_url: https://artifacts.apis.io/halo-collar/eligibility/halo-collar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Halo Collar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pet Tech
- Consumer IoT
- GPS Tracking
- Geofencing
- Wearables
- Connected Devices
- Mobile App
- Subscription Service
- Consumer Hardware
---
