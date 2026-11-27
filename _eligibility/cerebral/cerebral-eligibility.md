---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - SD
    - IR
    - KP
    - SY
    served:
    - US
    text: Access to and use of the Platform or the Services is limited exclusively to users located in states within the United States where the Services are available as identified on the Platform. Trade restrictions name Cuba, Sudan, Iran, North Korea and Syria.
  entity_types:
  - text: you represent and warrant that you are a natural person
    type: individual
  minimum_age:
    text: No Users Under 6 Years Old. Only users, or their parents or legal guardians, who have accepted these Terms of Use and are age 6 and older
    value: '6'
  restricted_uses:
  - summary: Not for emergencies
    text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL OR MENTAL HEALTH NEEDS.
  - summary: Government health program enrollees
    text: if you are insured under or covered by any of these programs, you are not permitted to use the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- SD
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cerebral
provenance_date: '2026-11-09'
provider_name: Cerebral
provider_slug: cerebral
slug: cerebral-eligibility
source_date: '2026-11-09'
source_filename: cerebral-eligibility.yml
source_heading: Eligibility
source_page: https://cerebral.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cerebral\naid: cerebral\nurl: https://cerebral.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - SD\n  - IR\n  - KP\n  - SY\n  text: Access to and use of the Platform or the Services is limited exclusively to users located in states within\n    the United States where the Services are available as identified on the Platform. Trade restrictions name Cuba,\n    Sudan, Iran, North Korea and Syria.\nentity_types:\n- type: individual\n  text: you represent and warrant that you are a natural person\nrestricted_uses:\n- summary: Not for emergencies\n\
  \  text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL OR MENTAL HEALTH NEEDS.\n- summary: Government health program enrollees\n  text: if you are insured under or covered by any of these programs, you are not permitted to use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '6'\n  text: No Users Under 6 Years Old. Only users, or their parents or legal guardians, who have accepted these Terms\n    of Use and are age 6 and older\n"
source_yaml_url: https://artifacts.apis.io/cerebral/eligibility/cerebral-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cerebral's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Health
- Mental Health
- Telehealth
- Healthcare
- Wellness
---
