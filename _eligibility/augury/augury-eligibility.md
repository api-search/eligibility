---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: (b) that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Private, non-commercial use only
    text: use the Services (including any webpage and/or data that passes through our web domain), domain names, URLs, databases, functions or its content other than for private, non-commercial purposes.
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
name: Augury
provenance_date: '2026-11-09'
provider_name: Augury
provider_slug: augury
slug: augury-eligibility
source_date: '2026-11-09'
source_filename: augury-eligibility.yml
source_heading: Eligibility
source_page: https://www.augury.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Augury\naid: augury\nurl: https://www.augury.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Private, non-commercial use only\n  text: use the Services (including any webpage and/or data that passes through our web domain), domain names, URLs,\n    databases, functions or its content other than for private, non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (b) that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/augury/eligibility/augury-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Augury's own page on 2026-11-09.
synthetic: false
tags:
- Industrial AI
- Machine Health
- Process Health
- Predictive Maintenance
- Vibration Analysis
- Condition Monitoring
- IoT Sensors
- Halo
- Manufacturing
- Reliability
- Asset Performance
- OT
- CMMS
- EAM
---
