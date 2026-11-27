---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When you use the Services, you represent that you are (i) at least the age of majority in the jurisdiction where you reside or (ii) if you have not reached the age of majority in the jurisdiction where you reside, that you have received permission to use the Services from your parent or legal guardian.
    type: individual
  minimum_age:
    text: at least the age of majority in the jurisdiction where you reside
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use the Service for any illegal or unauthorized purpose.
  - summary: Offensive or reputation-harming actions
    text: are patently offensive in any manner (as determined in our sole discretion)
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
name: Powerplay
provenance_date: '2026-11-10'
provider_name: Powerplay
provider_slug: powerplay
slug: powerplay-eligibility
source_date: '2026-11-10'
source_filename: powerplay-eligibility.yml
source_heading: Eligibility
source_page: https://www.getpowerplay.in/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Powerplay\naid: powerplay\nurl: https://www.getpowerplay.in/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: When you use the Services, you represent that you are (i) at least the age of majority in the jurisdiction\n    where you reside or (ii) if you have not reached the age of majority in the jurisdiction where you reside, that\n    you have received permission to use the Services from your parent or legal guardian.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use the Service for any\
  \ illegal or unauthorized purpose.\n- summary: Offensive or reputation-harming actions\n  text: are patently offensive in any manner (as determined in our sole discretion)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: at least the age of majority in the jurisdiction where you reside\n"
source_yaml_url: https://artifacts.apis.io/powerplay/eligibility/powerplay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Powerplay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Construction
- Construction Technology
- Project Management
- Field Service Management
- Payroll
- Mobile App
---
