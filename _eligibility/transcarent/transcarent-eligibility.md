---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Care Providers will only be permitted to render medical care to you if you are located in a state and jurisdiction in the United States of America in which such Care Providers are licensed to practice medicine.
  entity_types:
  - text: IF YOU ARE AN ENTITY, ORGANIZATION, OR COMPANY, THE INDIVIDUAL ACCEPTING THESE TERMS ON YOUR BEHALF REPRESENTS AND WARRANTS THAT THEY HAVE AUTHORITY TO BIND YOU TO THESE TERMS
    type: business
  - text: you may use the Service only if you are at least 12 years old and under the supervision of a parent or legal guardian who agrees to be bound by this Agreement.
    type: individual
  minimum_age:
    text: YOU ARE AT LEAST 18 YEARS OLD OR FULLY COMPLY WITH THE TERMS APPLICABLE TO INDIVIDUALS UNDER 18 YEARS OF AGE SET FORTH BELOW
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies
    text: The Service should not be used during a medical emergency.
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
name: Transcarent
provenance_date: '2026-11-10'
provider_name: Transcarent
provider_slug: transcarent
slug: transcarent-eligibility
source_date: '2026-11-10'
source_filename: transcarent-eligibility.yml
source_heading: Eligibility
source_page: https://transcarent.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Transcarent\naid: transcarent\nurl: https://transcarent.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Care Providers will only be permitted to render medical care to you if you are located in a state and\n    jurisdiction in the United States of America in which such Care Providers are licensed to practice medicine.\nentity_types:\n- type: business\n  text: IF YOU ARE AN ENTITY, ORGANIZATION, OR COMPANY, THE INDIVIDUAL ACCEPTING THESE TERMS ON YOUR BEHALF REPRESENTS\n    AND WARRANTS THAT THEY HAVE AUTHORITY TO BIND YOU TO THESE\
  \ TERMS\n- type: individual\n  text: you may use the Service only if you are at least 12 years old and under the supervision of a parent or legal\n    guardian who agrees to be bound by this Agreement.\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: The Service should not be used during a medical emergency.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: When you register for an account, you will be required to provide us with information about yourself, so\n    that we can verify your identity.\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST 18 YEARS OLD OR FULLY COMPLY WITH THE TERMS APPLICABLE TO INDIVIDUALS UNDER 18 YEARS OF\n    AGE SET FORTH BELOW\n"
source_yaml_url: https://artifacts.apis.io/transcarent/eligibility/transcarent-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Transcarent's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Benefits Navigation
- Care Navigation
- Virtual Care
- Artificial Intelligence
- Health Benefits
---
