---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Services is limited to healthcare professionals who are United States residents and at least 21 years of age.
  minimum_age:
    text: you are at least 21 years of age
    value: '21'
  restricted_uses:
  - summary: Non-commercial research or education only
    text: for internal, non-commercial use for non-profit research or educational purposes only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You authorize Dorsata to confirm the truthfulness and accuracy of the Registration Data and Conflict of Interest Disclosure.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dorsata
provenance_date: '2026-11-09'
provider_name: Dorsata
provider_slug: dorsata
slug: dorsata-eligibility
source_date: '2026-11-09'
source_filename: dorsata-eligibility.yml
source_heading: Eligibility
source_page: https://dorsata.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dorsata\naid: dorsata\nurl: https://dorsata.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Services is limited to healthcare professionals who are United States residents\n    and at least 21 years of age.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial research or education only\n  text: for internal, non-commercial use for non-profit research or educational purposes only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You authorize Dorsata to confirm the truthfulness and accuracy of\
  \ the Registration Data and Conflict of\n    Interest Disclosure.\nminimum_age:\n  value: '21'\n  text: you are at least 21 years of age\n"
source_yaml_url: https://artifacts.apis.io/dorsata/eligibility/dorsata-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Dorsata's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Health
- Electronic Health Records
- Obstetrics
- Women's Health
- Prenatal
- Clinical Data
- Software-as-a-Service
---
