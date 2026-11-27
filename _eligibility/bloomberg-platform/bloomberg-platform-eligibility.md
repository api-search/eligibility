---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg makes no representation that materials in this site are appropriate or available for use in other locations.
  entity_types:
  - text: 'You represent, warrant and covenant that: (i) you have the power and authority to enter into this agreement; and (ii) you are at least eighteen (18) years old.'
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity of your registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bloomberg Platform
provenance_date: '2026-11-09'
provider_name: Bloomberg Platform
provider_slug: bloomberg-platform
slug: bloomberg-platform-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-platform-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Platform\naid: bloomberg-platform\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg makes no representation that materials in this site are appropriate or available for use in other\n    locations.\nentity_types:\n- type: individual\n  text: 'You represent, warrant and covenant that: (i) you have the power and authority to enter into this agreement;\n    and (ii) you are at least eighteen (18) years old.'\nrestricted_uses:\n- summary: Illegal purposes\n  text: You may not use the Service for any illegal\
  \ purpose, for the facilitation of the violation of any law or\n    regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity\n    of your registration information.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-platform/eligibility/bloomberg-platform-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bloomberg Platform's own page on 2026-11-09.
synthetic: false
tags:
- Platform
- Infrastructure
- Data Distribution
- API Gateway
- Integration
- Bloomberg
---
