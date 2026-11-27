---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our Website is not intended for those under the age of 16 – if you access this Website or the Services, you represent and warrant that you are at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Patient identifying information
    text: If you are a health care provider, submit any information that would directly identify a patient or any information for which you do not have all necessary consents or authorizations to disclose
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
name: Radionetics Oncology
provenance_date: '2026-11-10'
provider_name: Radionetics Oncology
provider_slug: radionetics-oncology
slug: radionetics-oncology-eligibility
source_date: '2026-11-10'
source_filename: radionetics-oncology-eligibility.yml
source_heading: Eligibility
source_page: https://radionetics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Radionetics Oncology\naid: radionetics-oncology\nurl: https://radionetics.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Patient identifying information\n  text: If you are a health care provider, submit any information that would directly identify a patient or any\n    information for which you do not have all necessary consents or authorizations to disclose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Our Website is not intended for\
  \ those under the age of 16 – if you access this Website or the Services,\n    you represent and warrant that you are at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/radionetics-oncology/eligibility/radionetics-oncology-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Radionetics Oncology's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Radiopharmaceuticals
- Oncology
- Precision Medicine
- Life Sciences
- Healthcare
---
