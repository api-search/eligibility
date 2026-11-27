---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old and possess the legal capacity to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and possess the legal capacity to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: THE SERVICE IS NOT DESIGNED FOR OR INTENDED FOR EMERGENCY USE. IF YOU HAVE A MEDICAL EMERGENCY, CALL 9-1-1 IMMEDIATELY.
  - summary: Medical services only where licensed
    text: Medical Services are only available in jurisdictions where the applicable Newdays Practice and Providers are licensed and authorized to provide such services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access most features of the Service, you or your Caregiver must register for an account. During registration, you may be required to provide us with information about yourself
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NewDays
provenance_date: '2026-11-10'
provider_name: NewDays
provider_slug: newdays
slug: newdays-eligibility
source_date: '2026-11-10'
source_filename: newdays-eligibility.yml
source_heading: Eligibility
source_page: https://app.newdays.ai/legal/terms-of-use?back=false
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NewDays\naid: newdays\nurl: https://app.newdays.ai/legal/terms-of-use?back=false\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and possess the legal capacity to use the Service.\nrestricted_uses:\n- summary: Not for emergencies\n  text: THE SERVICE IS NOT DESIGNED FOR OR INTENDED FOR EMERGENCY USE. IF YOU HAVE A MEDICAL\
  \ EMERGENCY, CALL 9-1-1\n    IMMEDIATELY.\n- summary: Medical services only where licensed\n  text: Medical Services are only available in jurisdictions where the applicable Newdays Practice and Providers\n    are licensed and authorized to provide such services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access most features of the Service, you or your Caregiver must register for an account. During registration,\n    you may be required to provide us with information about yourself\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and possess the legal capacity to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/newdays/eligibility/newdays-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from NewDays's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Cognitive Health
- Dementia
- Telehealth
- Digital Therapeutics
- Artificial Intelligence
- Medicare
---
