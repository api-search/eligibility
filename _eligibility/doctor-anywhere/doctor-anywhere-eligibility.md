---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - SG
    text: The Healthcare Services are intended to be provided to users in Singapore and the Healthcare Providers are not qualified/licensed to consult/treat users outside Singapore
  entity_types:
  - text: you are at least 18 years of age
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No video consultation for emergencies
    text: 'IMPORTANT: DO NOT USE THE VIDEO CONSULTATION FUNCTIONALITY ON THE APPLICATION FOR A MEDICAL EMERGENCY.'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You authorize us to make any enquiries we consider necessary to validate and verify your identity (whether directly or through third parties) at any time for any reason whatsoever.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Doctor Anywhere
provenance_date: '2026-11-09'
provider_name: Doctor Anywhere
provider_slug: doctor-anywhere
slug: doctor-anywhere-eligibility
source_date: '2026-11-09'
source_filename: doctor-anywhere-eligibility.yml
source_heading: Eligibility
source_page: https://doctoranywhere.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doctor Anywhere\naid: doctor-anywhere\nurl: https://doctoranywhere.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - SG\n  excluded: []\n  text: The Healthcare Services are intended to be provided to users in Singapore and the Healthcare Providers are\n    not qualified/licensed to consult/treat users outside Singapore\nentity_types:\n- type: individual\n  text: you are at least 18 years of age\nrestricted_uses:\n- summary: No video consultation for emergencies\n  text: 'IMPORTANT: DO NOT USE THE VIDEO CONSULTATION FUNCTIONALITY ON THE APPLICATION FOR A MEDICAL\
  \ EMERGENCY.'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You authorize us to make any enquiries we consider necessary to validate and verify your identity (whether\n    directly or through third parties) at any time for any reason whatsoever.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/doctor-anywhere/eligibility/doctor-anywhere-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Doctor Anywhere's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Digital Health
- Health Screening
- Corporate Wellness
- Singapore
- Southeast Asia
- MCP
---
