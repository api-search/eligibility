---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: US & Canada, expanding globally
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
name: Sophtron
provenance_date: '2026-11-10'
provider_name: Sophtron
provider_slug: sophtron
slug: sophtron-eligibility
source_date: '2026-11-10'
source_filename: sophtron-eligibility.yml
source_heading: Eligibility
source_page: https://sophtron.com/developerAgreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sophtron\naid: sophtron\nurl: https://sophtron.com/developerAgreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: US & Canada, expanding globally\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sophtron/eligibility/sophtron-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Sophtron's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Data Aggregation
- Banking
- Financial Services
---
