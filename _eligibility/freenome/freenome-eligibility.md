---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  minimum_age:
    text: You must be at least eighteen (18) years of age to access and/or use this Website.
    value: '18'
  restricted_uses:
  - summary: Commercial purposes prohibited
    text: Access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
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
name: Freenome
provenance_date: '2026-11-09'
provider_name: Freenome
provider_slug: freenome
slug: freenome-eligibility
source_date: '2026-11-09'
source_filename: freenome-eligibility.yml
source_heading: Eligibility
source_page: https://www.freenome.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freenome\naid: freenome\nurl: https://www.freenome.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Commercial purposes prohibited\n  text: Access or use for any commercial purposes any part of the Website or any services or materials available\n    through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age\
  \ to access and/or use this Website.\n"
source_yaml_url: https://artifacts.apis.io/freenome/eligibility/freenome-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Freenome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Cancer Detection
- Diagnostics
- Life Sciences
- Artificial Intelligence
- Machine Learning
- Multiomics
- Clinical Screening
---
