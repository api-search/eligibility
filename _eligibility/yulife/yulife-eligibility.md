---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: You're on the United Kingdom version of the site.
  entity_types:
  - text: Your business has purchased a qualifying MetLife insurance product.
    type: business
  - text: Users include all individuals you allow to access and use the YuLife App (End User)
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Yulife
provenance_date: '2026-11-10'
provider_name: Yulife
provider_slug: yulife
slug: yulife-eligibility
source_date: '2026-11-10'
source_filename: yulife-eligibility.yml
source_heading: Eligibility
source_page: https://yulife.com/metlife-yulife-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yulife\naid: yulife\nurl: https://yulife.com/metlife-yulife-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: You're on the United Kingdom version of the site.\nentity_types:\n- type: business\n  text: Your business has purchased a qualifying MetLife insurance product.\n- type: individual\n  text: Users include all individuals you allow to access and use the YuLife App (End User)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yulife/eligibility/yulife-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from Yulife's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Employee Benefits
- Wellbeing
- Group Life Insurance
- Health Insurance
- B Corp
---
