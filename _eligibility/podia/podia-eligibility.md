---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered only for your own personal use and you may not use the Services on behalf of or for the benefit of any third party.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 16 years of age. If you are under age 16, you may not, under any circumstances or for any reason, access or use the Services.
    value: '16'
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
name: Podia
provenance_date: '2026-11-10'
provider_name: Podia
provider_slug: podia
slug: podia-eligibility
source_date: '2026-11-10'
source_filename: podia-eligibility.yml
source_heading: Eligibility
source_page: https://www.podia.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Podia\naid: podia\nurl: https://www.podia.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are offered only for your own personal use and you may not use the Services on behalf of or\n    for the benefit of any third party.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You represent and warrant that you are at least 16 years of age. If you are under age 16, you may not, under\n    any circumstances\
  \ or for any reason, access or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/podia/eligibility/podia-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Podia's own page on 2026-11-10.
synthetic: false
tags:
- Creator Economy
- Online Courses
- Digital Products
- Membership
- Email Marketing
- Zapier Only
- Creator Platform
- Community
- Website Builder
- Client-Side JavaScript
---
