---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website is intended only for users who reside in the United States of America and who are 18 years of age or older.
  entity_types:
  - text: This website is intended only for users who reside in the United States of America and who are 18 years of age or older.
    type: individual
  minimum_age:
    text: who are 18 years of age or older
    value: '18'
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
name: RayzeBio
provenance_date: '2026-11-10'
provider_name: RayzeBio
provider_slug: rayzebio
slug: rayzebio-eligibility
source_date: '2026-11-10'
source_filename: rayzebio-eligibility.yml
source_heading: Eligibility
source_page: https://rayzebio.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RayzeBio\naid: rayzebio\nurl: https://rayzebio.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website is intended only for users who reside in the United States of America and who are 18 years\n    of age or older.\nentity_types:\n- type: individual\n  text: This website is intended only for users who reside in the United States of America and who are 18 years\n    of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/rayzebio/eligibility/rayzebio-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from RayzeBio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Oncology
- Radiopharmaceuticals
- Life Sciences
- Healthcare
- Clinical Trials
- Drug Discovery
---
