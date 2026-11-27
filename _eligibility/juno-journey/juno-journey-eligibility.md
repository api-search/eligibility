---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - LB
    - KP
    - SY
    served: []
    text: Customer agrees not to use... the Services in violation of any applicable U.S., Israeli, or other export control laws or sanctions, including to any person or entity (i) located in or ordinarily resident of a sanctioned territory (e.g., Cuba, Iran, Lebanon, North Korea, Syria, or Crimea)
  entity_types:
  - text: Services are for business use only and are not provided for individual consumer use.
    type: business
  minimum_age:
    text: Persons who are less than 18 years of age are not permitted to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: Customer further agrees not to use, export, re-export, transfer, or make the Services available in violation of any applicable U.S., Israeli, or other export control laws or sanctions
  - summary: Impersonation
    text: impersonate any person or entity, or otherwise misrepresent its affiliation with a person or entity;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- LB
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Juno Journey
provenance_date: '2026-11-09'
provider_name: Juno Journey
provider_slug: juno-journey
slug: juno-journey-eligibility
source_date: '2026-11-09'
source_filename: juno-journey-eligibility.yml
source_heading: Eligibility
source_page: https://www.junojourney.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juno Journey\naid: juno-journey\nurl: https://www.junojourney.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - LB\n  - KP\n  - SY\n  text: Customer agrees not to use... the Services in violation of any applicable U.S., Israeli, or other export\n    control laws or sanctions, including to any person or entity (i) located in or ordinarily resident of a sanctioned\n    territory (e.g., Cuba, Iran, Lebanon, North Korea, Syria, or Crimea)\nentity_types:\n- type: business\n  text: Services are for business use only and are not provided for individual consumer\
  \ use.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Customer further agrees not to use, export, re-export, transfer, or make the Services available in violation\n    of any applicable U.S., Israeli, or other export control laws or sanctions\n- summary: Impersonation\n  text: impersonate any person or entity, or otherwise misrepresent its affiliation with a person or entity;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons who are less than 18 years of age are not permitted to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/juno-journey/eligibility/juno-journey-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Juno Journey's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Learning and Development
- LMS
- Human Resources
- Employee Training
- Performance Management
- Skills Analytics
- Artificial Intelligence
- Software-as-a-Service
---
