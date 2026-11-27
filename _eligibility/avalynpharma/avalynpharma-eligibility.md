---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website is intended only for users who reside in the United States of America and who are 18 years of age or older.
  minimum_age:
    text: who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Not a substitute for medical advice
    text: The content and information on the Site are in no way intended to replace professional medical advice, diagnosis or treatment.
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
name: Avalynpharma
provenance_date: '2026-11-09'
provider_name: Avalynpharma
provider_slug: avalynpharma
slug: avalynpharma-eligibility
source_date: '2026-11-09'
source_filename: avalynpharma-eligibility.yml
source_heading: Eligibility
source_page: https://www.avalynpharma.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avalynpharma\naid: avalynpharma\nurl: https://www.avalynpharma.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website is intended only for users who reside in the United States of America and who are 18 years\n    of age or older.\nentity_types: []\nrestricted_uses:\n- summary: Not a substitute for medical advice\n  text: The content and information on the Site are in no way intended to replace professional medical advice, diagnosis\n    or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/avalynpharma/eligibility/avalynpharma-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Avalynpharma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Clinical Stage
- Respiratory
- Pulmonary Fibrosis
- Inhaled Therapeutics
- Life Sciences
---
