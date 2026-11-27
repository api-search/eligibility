---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: THESE TERMS APPLY IF YOU LIVE IN THE UNITED STATES OR IF YOUR PRINCIPAL PLACE OF BUSINESS IS IN THE UNITED STATES. IF YOU LIVE OUTSIDE OF THE UNITED STATES OR IF YOUR PRINCIPAL PLACE OF BUSINESS IS OUTSIDE OF THE UNITED STATES NUNA MAKES NO REPRESENTATION THAT SERVICES AND/OR MATERIAL DESCRIBED OR AVAILABLE THROUGH THE SERVICES ARE APPROPRIATE OR AVAILABLE FOR USE IN LOCATIONS OUTSIDE THE UNITED STATES.
  entity_types:
  - text: 'Partner Users: Users who download and install the App through an invitation from a partner program (such as employers, hospitals, insurers, or clinical providers).'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for emergencies
    text: USE OF THE SERVICES IS NOT FOR EMERGENCIES. IF YOU THINK YOU HAVE A MEDICAL EMERGENCY, CALL 911 OR GO TO THE NEAREST OPEN CLINIC OR EMERGENCY ROOM.
  - summary: Non-commercial personal use of App
    text: to run the App solely for your own personal non-commercial purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the App, you must create an account and provide accurate, complete, and current basic information about yourself.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nuna
provenance_date: '2026-11-10'
provider_name: Nuna
provider_slug: nuna
slug: nuna-eligibility
source_date: '2026-11-10'
source_filename: nuna-eligibility.yml
source_heading: Eligibility
source_page: https://www.nuna.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nuna\naid: nuna\nurl: https://www.nuna.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: THESE TERMS APPLY IF YOU LIVE IN THE UNITED STATES OR IF YOUR PRINCIPAL PLACE OF BUSINESS IS IN THE UNITED\n    STATES. IF YOU LIVE OUTSIDE OF THE UNITED STATES OR IF YOUR PRINCIPAL PLACE OF BUSINESS IS OUTSIDE OF THE UNITED\n    STATES NUNA MAKES NO REPRESENTATION THAT SERVICES AND/OR MATERIAL DESCRIBED OR AVAILABLE THROUGH THE SERVICES\n    ARE APPROPRIATE OR AVAILABLE FOR USE IN LOCATIONS OUTSIDE THE UNITED STATES.\nentity_types:\n- type: business\n  text: 'Partner\
  \ Users: Users who download and install the App through an invitation from a partner program (such\n    as employers, hospitals, insurers, or clinical providers).'\nrestricted_uses:\n- summary: Not for emergencies\n  text: USE OF THE SERVICES IS NOT FOR EMERGENCIES. IF YOU THINK YOU HAVE A MEDICAL EMERGENCY, CALL 911 OR GO TO\n    THE NEAREST OPEN CLINIC OR EMERGENCY ROOM.\n- summary: Non-commercial personal use of App\n  text: to run the App solely for your own personal non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the App, you must create an account and provide accurate, complete, and current basic information\n    about yourself.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nuna/eligibility/nuna-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Nuna's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Data
- Medicaid
- Medicare
- Analytics
- Chronic Care
- Digital Health
- Artificial Intelligence
- Mobile
---
