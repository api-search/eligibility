---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you can form a binding contract with Get Covered
    type: individual
  - text: If you are accessing the Services on behalf of your company, you represent and warranty that you have authority to bind your company to this Agreement.
    type: business
  minimum_age:
    text: Any use or access by anyone under 13 is strictly prohibited.
    value: '13'
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
name: Get Covered
provenance_date: '2026-11-09'
provider_name: Get Covered
provider_slug: get-covered
slug: get-covered-eligibility
source_date: '2026-11-09'
source_filename: get-covered-eligibility.yml
source_heading: Eligibility
source_page: https://www.getcovered.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Get Covered\naid: get-covered\nurl: https://www.getcovered.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you can form a binding contract with Get Covered\n- type: business\n  text: If you are accessing the Services on behalf of your company, you represent and warranty that you have authority\n    to bind your company to this Agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access\
  \ by anyone under 13 is strictly prohibited.\n"
source_yaml_url: https://artifacts.apis.io/get-covered/eligibility/get-covered-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Get Covered's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Renters Insurance
- Property Management
- Real Estate
- Compliance
- Risk Management
- Embedded Insurance
- Artificial Intelligence
---
