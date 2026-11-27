---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your personal, non-commercial use on a mobile device owned or otherwise controlled by you
    type: individual
  minimum_age:
    text: REPRESENT THAT YOU ARE EIGHTEEN (18) YEARS OF AGE OR OLDER
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: The Services and Telehealth Services are not intended for use in the event of an emergency.
  - summary: Not for children
    text: Children under the age of eighteen (18) years old are prohibited from using the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company and Medical Group may contact you by telephone, mail, or email to verify your account information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rightway
provenance_date: '2026-11-10'
provider_name: Rightway
provider_slug: rightway
slug: rightway-eligibility
source_date: '2026-11-10'
source_filename: rightway-eligibility.yml
source_heading: Eligibility
source_page: https://www.rightwayhealthcare.com/terms-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rightway\naid: rightway\nurl: https://www.rightwayhealthcare.com/terms-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your personal, non-commercial use on a mobile device owned or otherwise controlled by you\nrestricted_uses:\n- summary: Not for emergencies\n  text: The Services and Telehealth Services are not intended for use in the event of an emergency.\n- summary: Not for children\n  text: Children under the age of eighteen (18) years old are prohibited from using the Service.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: The Company and Medical Group may contact you by telephone, mail, or email to verify your account information.\nminimum_age:\n  value: '18'\n  text: REPRESENT THAT YOU ARE EIGHTEEN (18) YEARS OF AGE OR OLDER\n"
source_yaml_url: https://artifacts.apis.io/rightway/eligibility/rightway-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rightway's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy Benefits
- PBM
- Care Navigation
- Health Insurance
- Employee Benefits
- Digital Health
- HIPAA
---
