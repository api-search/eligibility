---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is offered and available to users who are 13 years of age or older and reside in the United States.
  entity_types:
  - text: Users who are 13 years of age or older and reside in the United States.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 13 years of age or older
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
name: Mission Barns
provenance_date: '2026-11-10'
provider_name: Mission Barns
provider_slug: missionbarns
slug: missionbarns-eligibility
source_date: '2026-11-10'
source_filename: missionbarns-eligibility.yml
source_heading: Eligibility
source_page: https://missionbarns.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mission Barns\naid: missionbarns\nurl: https://missionbarns.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is offered and available to users who are 13 years of age or older and reside in the United\n    States.\nentity_types:\n- type: individual\n  text: Users who are 13 years of age or older and reside in the United States.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Website is offered and available to users who are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/missionbarns/eligibility/missionbarns-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Mission Barns's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food Technology
- Cultivated Meat
- Cellular Agriculture
- Biotechnology
- Sustainability
- Consumer Packaged Goods
---
