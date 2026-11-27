---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will not use the Site or Services if you are located in a country where such use is prohibited by the applicable law.
  entity_types:
  - text: Infogram’s Free / Basic plan is only available to individual users
    type: individual
  - text: Business, Team or Enterprise customer
    type: business
  minimum_age:
    text: YOU AGREE THAT BY USING THE SERVICE YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD
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
name: Infogram
provenance_date: '2026-11-09'
provider_name: Infogram
provider_slug: infogram
slug: infogram-eligibility
source_date: '2026-11-09'
source_filename: infogram-eligibility.yml
source_heading: Eligibility
source_page: https://infogram.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infogram\naid: infogram\nurl: https://infogram.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will not use the Site or Services if you are located in a country where such use is prohibited by the\n    applicable law.\nentity_types:\n- type: individual\n  text: Infogram’s Free / Basic plan is only available to individual users\n- type: business\n  text: Business, Team or Enterprise customer\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU AGREE THAT BY USING THE SERVICE YOU\
  \ REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/infogram/eligibility/infogram-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Infogram's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Visualization
- Infographics
- Charts
- Dashboards
- Reporting
- Business Intelligence
- Content
- Embed
---
