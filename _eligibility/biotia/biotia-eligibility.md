---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Services are not available to anyone located or residing outside of the United States of America.
  entity_types:
  - text: the individual user who has elected to access and use the Services
    type: individual
  minimum_age:
    text: you are at least 18 years of age, of the age of majority in your state
    value: '18'
  restricted_uses:
  - summary: Telehealth only in licensed states
    text: telehealth services are only available in states where Providers are licensed to practice, and you must be physically located in an eligible state at the time of any telehealth consultation.
  - summary: Not for medical emergencies
    text: The Services are not designed or intended for use in medical emergencies or urgent care situations.
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
name: Biotia
provenance_date: '2026-11-09'
provider_name: Biotia
provider_slug: biotia
slug: biotia-eligibility
source_date: '2026-11-09'
source_filename: biotia-eligibility.yml
source_heading: Eligibility
source_page: https://biotia.io/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biotia\naid: biotia\nurl: https://biotia.io/user-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Services are not available to anyone located or residing outside of the United States of America.\nentity_types:\n- type: individual\n  text: the individual user who has elected to access and use the Services\nrestricted_uses:\n- summary: Telehealth only in licensed states\n  text: telehealth services are only available in states where Providers are licensed to practice, and you must\n    be physically located in an eligible state at the time of any telehealth consultation.\n\
  - summary: Not for medical emergencies\n  text: The Services are not designed or intended for use in medical emergencies or urgent care situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age, of the age of majority in your state\n"
source_yaml_url: https://artifacts.apis.io/biotia/eligibility/biotia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Biotia's own page on 2026-11-09.
synthetic: false
tags:
- Health Tech
- Diagnostics
- Infectious Diseases
- Biotechnology
- Company
---
