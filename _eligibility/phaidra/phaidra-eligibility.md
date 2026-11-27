---
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: you are not in a country where such export, re-export, or transfer is prohibited
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: You expressly agree to comply with such restrictions and not to export, re-export, or transfer any of the Content to countries or persons prohibited under the applicable Trade Restrictions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Phaidra
provenance_date: '2026-11-10'
provider_name: Phaidra
provider_slug: phaidra
slug: phaidra-eligibility
source_date: '2026-11-10'
source_filename: phaidra-eligibility.yml
source_heading: Eligibility
source_page: https://www.phaidra.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phaidra\naid: phaidra\nurl: https://www.phaidra.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: you are not in a country where such export, re-export, or transfer is prohibited\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: You expressly agree to comply with such restrictions and not to export, re-export, or transfer any of the\n    Content to countries or persons prohibited under the applicable Trade Restrictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/phaidra/eligibility/phaidra-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Phaidra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data Center
- Industrial Automation
- Reinforcement Learning
- Energy Efficiency
- Autonomous Control
---
