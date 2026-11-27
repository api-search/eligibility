---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must be a resident of any country where the Service is made available by Yoshi.
  entity_types:
  - text: You must be at least 18 years old to access and use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to access and use the Service.
    value: '18'
  restricted_uses:
  - summary: Use only as expressly permitted
    text: you may use the Service only as expressly permitted in these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration requires a valid, working e-mail address and other information in order to initially signup for access to and use of the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yoshi
provenance_date: '2026-11-10'
provider_name: Yoshi
provider_slug: yoshi
slug: yoshi-eligibility
source_date: '2026-11-10'
source_filename: yoshi-eligibility.yml
source_heading: Eligibility
source_page: https://www.yoshimobility.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yoshi\naid: yoshi\nurl: https://www.yoshimobility.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must be a resident of any country where the Service is made available by Yoshi.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to access and use the Service.\nrestricted_uses:\n- summary: Use only as expressly permitted\n  text: you may use the Service only as expressly permitted in these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration requires a valid, working e-mail address and other information\
  \ in order to initially signup\n    for access to and use of the Service.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to access and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/yoshi/eligibility/yoshi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Yoshi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Automotive
- Fleet Management
- Vehicle Inspections
- EV Charging
- Car Care
- Field Service Management
---
