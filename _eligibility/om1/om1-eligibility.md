---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is provided for use only by persons located in the United States.
  minimum_age:
    text: The Site may be accessed only by individuals who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Internal non-commercial use only
    text: You will access and use the Site solely for your internal, non-commercial purposes.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Registered Users may only access the subscription area of the Site with our approval and after executing a separate subscription agreement with us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Om1
provenance_date: '2026-11-10'
provider_name: Om1
provider_slug: om1
slug: om1-eligibility
source_date: '2026-11-10'
source_filename: om1-eligibility.yml
source_heading: Eligibility
source_page: https://www.om1.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Om1\naid: om1\nurl: https://www.om1.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is provided for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Internal non-commercial use only\n  text: You will access and use the Site solely for your internal, non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Registered Users may only access the subscription area of the Site with our approval and after executing\n    a separate subscription agreement with\
  \ us.\nminimum_age:\n  value: '18'\n  text: The Site may be accessed only by individuals who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/om1/eligibility/om1-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Om1's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Real-World Data
- Real-World Evidence
- Artificial Intelligence
- Machine Learning
- Analytics
- Life Sciences
- Clinical Data
- Data
---
