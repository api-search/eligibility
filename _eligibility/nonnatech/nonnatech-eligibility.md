---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services were created with the intent to be used by U.S. residents.
  entity_types:
  - text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  minimum_age:
    text: You affirm that you are either more than 18 years of age
    value: '18'
  restricted_uses:
  - summary: Not for medical emergency or diagnosis
    text: the content of this Site should not be used
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
name: Nonnatech
provenance_date: '2026-11-10'
provider_name: Nonnatech
provider_slug: nonnatech
slug: nonnatech-eligibility
source_date: '2026-11-10'
source_filename: nonnatech-eligibility.yml
source_heading: Eligibility
source_page: https://nonnatech.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nonnatech\naid: nonnatech\nurl: https://nonnatech.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services were created with the intent to be used by U.S. residents.\nentity_types:\n- type: individual\n  text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental\n    or guardian consent\nrestricted_uses:\n- summary: Not for medical emergency or diagnosis\n  text: the content of this Site should not be used\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You affirm that you are either more than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/nonnatech/eligibility/nonnatech-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nonnatech's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Remote Patient Monitoring
- Digital Health
- Telehealth
- HIPAA
- Population Health
- Chronic Care
---
