---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the Site or register an Almanac account.
    type: individual
  - text: If you are accessing the Site as a representative or employee of a company, this agreement is among Almanac, you personally, and your company.
    type: business
  minimum_age:
    text: You must be at least 18 years old
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
name: Almanac Leie1
provenance_date: '2026-11-09'
provider_name: Almanac Leie1
provider_slug: almanac-leie1
slug: almanac-leie1-eligibility
source_date: '2026-11-09'
source_filename: almanac-leie1-eligibility.yml
source_heading: Eligibility
source_page: https://get.almanac.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Almanac Leie1\naid: almanac-leie1\nurl: https://get.almanac.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the\n    Site or register an Almanac account.\n- type: business\n  text: If you are accessing the Site as a representative or employee of a company, this agreement is among Almanac,\n    you personally, and your company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/almanac-leie1/eligibility/almanac-leie1-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Almanac Leie1's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collaboration
- Documents
- Wiki
- Workflows
- Productivity
- Knowledge Management
---
