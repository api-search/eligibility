---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services include financial products or services that enable an individual who meets certain qualifications to use the Rain App to request and obtain, from time to time, a Rain Account
    type: individual
  minimum_age:
    text: If You are under 14 years of age, You may not use the Service in any way and You may not submit any information about yourself to Rain in any way.
    value: '14'
  restricted_uses:
  - summary: Lawful use only
    text: You shall use the Services lawfully and in good faith;
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
name: Rain
provenance_date: '2026-11-10'
provider_name: Rain
provider_slug: rainapp-com
slug: rainapp-com-eligibility
source_date: '2026-11-10'
source_filename: rainapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.rainapp.com/terms/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rain\naid: rainapp-com\nurl: https://www.rainapp.com/terms/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services include financial products or services that enable an individual who meets certain qualifications\n    to use the Rain App to request and obtain, from time to time, a Rain Account\nrestricted_uses:\n- summary: Lawful use only\n  text: You shall use the Services lawfully and in good faith;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '14'\n  text: If You are under 14 years of age, You may not use the Service in any way and You may not submit any information\n    about yourself to Rain in any way.\n"
source_yaml_url: https://artifacts.apis.io/rainapp-com/eligibility/rainapp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rain's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Health
- Employee Benefits
- Fintech
- Artificial Intelligence
---
