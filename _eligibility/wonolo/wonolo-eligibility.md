---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must be at least 18 years old [or the age of legal majority in the jurisdiction in which you work] and legally authorized to work in the United States to become a Wonoloer.
  entity_types:
  - text: Only individuals who can form legally binding contracts under applicable law are permitted to use the Application.
    type: individual
  minimum_age:
    text: you must be at least 18 years old [or the age of legal majority in the jurisdiction in which you work]
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
name: Wonolo
provenance_date: '2026-11-10'
provider_name: Wonolo
provider_slug: wonolo
slug: wonolo-eligibility
source_date: '2026-11-10'
source_filename: wonolo-eligibility.yml
source_heading: Eligibility
source_page: https://info.wonolo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wonolo\naid: wonolo\nurl: https://info.wonolo.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must be at least 18 years old [or the age of legal majority in the jurisdiction in which you work] and\n    legally authorized to work in the United States to become a Wonoloer.\nentity_types:\n- type: individual\n  text: Only individuals who can form legally binding contracts under applicable law are permitted to use the Application.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: you must be at least 18 years old [or the age of legal majority in the jurisdiction in which you work]\n"
source_yaml_url: https://artifacts.apis.io/wonolo/eligibility/wonolo-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Wonolo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Staffing
- Workforce
- Human Resources
- Marketplace
- Gig Economy
- Recruiting
- Labor
- On-Demand
---
