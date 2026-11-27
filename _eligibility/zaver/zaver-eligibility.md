---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Select your country to view the specific terms for your location.
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
name: Zaver
provenance_date: '2026-11-10'
provider_name: Zaver
provider_slug: zaver
slug: zaver-eligibility
source_date: '2026-11-10'
source_filename: zaver-eligibility.yml
source_heading: Eligibility
source_page: https://www.zaver.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zaver\naid: zaver\nurl: https://www.zaver.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Select your country to view the specific terms for your location.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zaver/eligibility/zaver-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Zaver's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- E-Commerce
- Software-as-a-Service
- Company
---
