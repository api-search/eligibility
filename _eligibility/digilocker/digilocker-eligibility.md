---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: users must register using a valid Indian mobile number, Driving License, PAN or Aadhaar
  entity_types:
  - text: Any individual who registers for and accesses the DigiLocker platform using a valid Indian mobile number, Driving License, PAN, or Aadhaar, and agrees to be bound by these Terms of Use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful content
    text: It is advisable to not upload, store, share, or disseminate any illegal, harmful, offensive, defamatory, exploitative, or otherwise objectionable contents under Indian law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration may require verification via an OTP.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DigiLocker
provenance_date: '2026-11-09'
provider_name: DigiLocker
provider_slug: digilocker
slug: digilocker-eligibility
source_date: '2026-11-09'
source_filename: digilocker-eligibility.yml
source_heading: Eligibility
source_page: https://www.digilocker.gov.in/web/about/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DigiLocker\naid: digilocker\nurl: https://www.digilocker.gov.in/web/about/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: users must register using a valid Indian mobile number, Driving License, PAN or Aadhaar\nentity_types:\n- type: individual\n  text: Any individual who registers for and accesses the DigiLocker platform using a valid Indian mobile number,\n    Driving License, PAN, or Aadhaar, and agrees to be bound by these Terms of Use.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: It is advisable to not upload, store, share, or disseminate any illegal,\
  \ harmful, offensive, defamatory,\n    exploitative, or otherwise objectionable contents under Indian law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration may require verification via an OTP.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/digilocker/eligibility/digilocker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from DigiLocker's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
