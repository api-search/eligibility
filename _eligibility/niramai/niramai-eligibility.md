---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Platform is controlled and offered by the Company from its facilities in India. The Company makes no representations that the Platform is appropriate or available for use in other locations.
  entity_types:
  - text: you are a natural / legal person who has attained the age of at least eighteen (18) years and is legally allowed to enter into a contract in India
    type: individual
  - text: you are a natural / legal person who has attained the age of at least eighteen (18) years and is legally allowed to enter into a contract in India
    type: business
  minimum_age:
    text: you are a natural / legal person who has attained the age of at least eighteen (18) years and is legally allowed to enter into a contract in India
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
name: Niramai
provenance_date: '2026-11-10'
provider_name: Niramai
provider_slug: niramai
slug: niramai-eligibility
source_date: '2026-11-10'
source_filename: niramai-eligibility.yml
source_heading: Eligibility
source_page: https://niramai.com/terms-of-use-and-privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Niramai\naid: niramai\nurl: https://niramai.com/terms-of-use-and-privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Platform is controlled and offered by the Company from its facilities in India. The Company makes no\n    representations that the Platform is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are a natural / legal person who has attained the age of at least eighteen (18) years and is legally\n    allowed to enter into a contract in India\n- type: business\n  text: you are a natural / legal person\
  \ who has attained the age of at least eighteen (18) years and is legally\n    allowed to enter into a contract in India\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are a natural / legal person who has attained the age of at least eighteen (18) years and is legally\n    allowed to enter into a contract in India\n"
source_yaml_url: https://artifacts.apis.io/niramai/eligibility/niramai-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Niramai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Machine Learning
- Medical Imaging
- Breast Cancer Screening
- Diagnostics
- Health Tech
---
