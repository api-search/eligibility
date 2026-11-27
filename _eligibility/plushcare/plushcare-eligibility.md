---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Care Providers will only be permitted to render medical care to you if you are located in a state and jurisdiction in the United States of America in which such Care Providers are licensed to practice medicine.
  entity_types:
  - text: 'BY AGREEING TO THESE TERMS, YOU REPRESENT AND WARRANT TO US THAT: (A) YOU ARE AT LEAST 18 YEARS OLD OR FULLY COMPLY WITH THE TERMS APPLICABLE TO INDIVIDUALS UNDER 18 YEARS OF AGE'
    type: individual
  - text: IF YOU ARE AN ENTITY, ORGANIZATION, OR COMPANY, THE INDIVIDUAL ACCEPTING THESE TERMS ON YOUR BEHALF REPRESENTS AND WARRANTS THAT THEY HAVE AUTHORITY TO BIND YOU TO THESE TERMS
    type: business
  minimum_age:
    text: (A) YOU ARE AT LEAST 18 YEARS OLD OR FULLY COMPLY WITH THE TERMS APPLICABLE TO INDIVIDUALS UNDER 18 YEARS OF AGE SET FORTH BELOW
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies
    text: The Service should not be used during a medical emergency. If you have a medical emergency, call 911 or proceed to your nearest Emergency Room immediately.
  - summary: Minors only under supervision
    text: A minor aged 12-17 may use the Service under the supervision and with the consent of a parent or legal guardian
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: When you register for an account, you will be required to provide us with information about yourself, so that we can verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PlushCare
provenance_date: '2026-11-10'
provider_name: PlushCare
provider_slug: plushcare
slug: plushcare-eligibility
source_date: '2026-11-10'
source_filename: plushcare-eligibility.yml
source_heading: Eligibility
source_page: https://plushcare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlushCare\naid: plushcare\nurl: https://plushcare.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Care Providers will only be permitted to render medical care to you if you are located in a state and\n    jurisdiction in the United States of America in which such Care Providers are licensed to practice medicine.\nentity_types:\n- type: individual\n  text: 'BY AGREEING TO THESE TERMS, YOU REPRESENT AND WARRANT TO US THAT: (A) YOU ARE AT LEAST 18 YEARS OLD OR\n    FULLY COMPLY WITH THE TERMS APPLICABLE TO INDIVIDUALS UNDER 18 YEARS OF AGE'\n- type:\
  \ business\n  text: IF YOU ARE AN ENTITY, ORGANIZATION, OR COMPANY, THE INDIVIDUAL ACCEPTING THESE TERMS ON YOUR BEHALF REPRESENTS\n    AND WARRANTS THAT THEY HAVE AUTHORITY TO BIND YOU TO THESE TERMS\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: The Service should not be used during a medical emergency. If you have a medical emergency, call 911 or\n    proceed to your nearest Emergency Room immediately.\n- summary: Minors only under supervision\n  text: A minor aged 12-17 may use the Service under the supervision and with the consent of a parent or legal guardian\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: When you register for an account, you will be required to provide us with information about yourself, so\n    that we can verify your identity.\nminimum_age:\n  value: '18'\n  text: (A) YOU ARE AT LEAST 18 YEARS OLD OR FULLY COMPLY WITH THE TERMS APPLICABLE TO INDIVIDUALS UNDER 18 YEARS\n    OF AGE SET FORTH BELOW\n"
source_yaml_url: https://artifacts.apis.io/plushcare/eligibility/plushcare-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from PlushCare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Telehealth
- Healthcare
- Primary Care
- Digital Health
- Mental Health
- Virtual Care
- Consumer Health
---
