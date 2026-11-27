---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Telehealth Services are intended for use by residents of the United States. We do not intentionally provide access to the Telehealth Services to individuals located outside the United States.
  entity_types:
  - text: User refers to an individual end user of the Services, who may be a patient of a healthcare provider, an employee or other staff or workforce member of an employer, or any other individual user
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: DO NOT USE THE SERVICES FOR EMERGENCY MEDICAL NEEDS.
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
name: Amwell
provenance_date: '2026-11-09'
provider_name: Amwell
provider_slug: amwell
slug: amwell-eligibility
source_date: '2026-11-09'
source_filename: amwell-eligibility.yml
source_heading: Eligibility
source_page: https://business.amwell.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amwell\naid: amwell\nurl: https://business.amwell.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Telehealth Services are intended for use by residents of the United States. We do not intentionally\n    provide access to the Telehealth Services to individuals located outside the United States.\nentity_types:\n- type: individual\n  text: User refers to an individual end user of the Services, who may be a patient of a healthcare provider, an\n    employee or other staff or workforce member of an employer, or any other individual user\nrestricted_uses:\n-\
  \ summary: Not for emergencies\n  text: DO NOT USE THE SERVICES FOR EMERGENCY MEDICAL NEEDS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/amwell/eligibility/amwell-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Amwell's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- Telehealth
- Virtual Care
- FHIR
- HL7
- Interoperability
- Electronic Health Records
- SDK
---
