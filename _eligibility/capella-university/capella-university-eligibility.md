---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Program is intended for use by U.S. residents who are at least 18 years of age.
  entity_types:
  - text: The Program is intended for use by U.S. residents who are at least 18 years of age.
    type: individual
  minimum_age:
    text: The Program is intended for use by U.S. residents who are at least 18 years of age.
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
name: Capella University
provenance_date: '2026-11-09'
provider_name: Capella University
provider_slug: capella-university
slug: capella-university-eligibility
source_date: '2026-11-09'
source_filename: capella-university-eligibility.yml
source_heading: Eligibility
source_page: https://www.capella.edu/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capella University\naid: capella-university\nurl: https://www.capella.edu/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Program is intended for use by U.S. residents who are at least 18 years of age.\nentity_types:\n- type: individual\n  text: The Program is intended for use by U.S. residents who are at least 18 years of age.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Program is intended for use by U.S. residents who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/capella-university/eligibility/capella-university-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Capella University's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Higher Education
- E-Learning
- University
- Competency-Based Education
- EdTech
---
