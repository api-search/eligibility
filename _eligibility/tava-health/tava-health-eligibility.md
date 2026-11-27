---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: provides this Application for your personal use within the United States.
  entity_types:
  - text: Anyone who accesses the Application, including clients and health care professionals, is referred to as “you” and “your.”
    type: individual
  minimum_age:
    text: By using the Application and the Services, you affirm that you are at least eighteen (18) years old, or that you have acquired the appropriate parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: No competitors
    text: You will not access the Services if you are a competitor of Tava Health, except with Tava Health’s prior written consent, or for any other competitive purposes;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We are entitled at all times to verify the information provided and to deny your use of the Services at any time for any reason or for no reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tava Health
provenance_date: '2026-11-10'
provider_name: Tava Health
provider_slug: tava-health
slug: tava-health-eligibility
source_date: '2026-11-10'
source_filename: tava-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.tavahealth.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tava Health\naid: tava-health\nurl: https://www.tavahealth.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: provides this Application for your personal use within the United States.\nentity_types:\n- type: individual\n  text: Anyone who accesses the Application, including clients and health care professionals, is referred to as\n    “you” and “your.”\nrestricted_uses:\n- summary: No competitors\n  text: You will not access the Services if you are a competitor of Tava Health, except with Tava Health’s prior\n    written consent, or for any other competitive\
  \ purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We are entitled at all times to verify the information provided and to deny your use of the Services at\n    any time for any reason or for no reason.\nminimum_age:\n  value: '18'\n  text: By using the Application and the Services, you affirm that you are at least eighteen (18) years old, or\n    that you have acquired the appropriate parental or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/tava-health/eligibility/tava-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Tava Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Behavioral Health
- Telehealth
- Employee Benefits
- Health Plans
- HIPAA
- Digital Health
- Care Delivery
---
