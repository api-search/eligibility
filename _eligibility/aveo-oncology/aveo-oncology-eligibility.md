---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website is intended for use by residents of the United States and its territories who are 18 years of age or older.
  minimum_age:
    text: intended for use by residents of the United States and its territories who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Information not medical advice
    text: You should not use the information contained herein for diagnosing a health or fitness problem or disease or advising on any treatment of any health or fitness problem or disease.
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
name: AVEO Oncology
provenance_date: '2026-11-09'
provider_name: AVEO Oncology
provider_slug: aveo-oncology
slug: aveo-oncology-eligibility
source_date: '2026-11-09'
source_filename: aveo-oncology-eligibility.yml
source_heading: Eligibility
source_page: https://www.aveooncology.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AVEO Oncology\naid: aveo-oncology\nurl: https://www.aveooncology.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website is intended for use by residents of the United States and its territories who are 18 years\n    of age or older.\nentity_types: []\nrestricted_uses:\n- summary: Information not medical advice\n  text: You should not use the information contained herein for diagnosing a health or fitness problem or disease\n    or advising on any treatment of any health or fitness problem or disease.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: intended for use by residents of the United States and its territories who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/aveo-oncology/eligibility/aveo-oncology-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AVEO Oncology's own page on 2026-11-09.
synthetic: false
tags:
- Oncology
- Biopharmaceutical
- Cancer
- Pharmaceuticals
- Partnerships
---
