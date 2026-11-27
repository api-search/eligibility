---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be a citizen or permanent legal resident of the United States and have a Social Security Number or Taxpayer ID.
  entity_types:
  - text: You must be at least 18 years old.
    type: individual
  - text: You may be permitted to open a Business Account.
    type: business
  minimum_age:
    text: You must be at least 18 years old.
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
name: River Financial
provenance_date: '2026-11-10'
provider_name: River Financial
provider_slug: river-financial
slug: river-financial-eligibility
source_date: '2026-11-10'
source_filename: river-financial-eligibility.yml
source_heading: Eligibility
source_page: https://river.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: River Financial\naid: river-financial\nurl: https://river.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be a citizen or permanent legal resident of the United States and have a Social Security Number\n    or Taxpayer ID.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old.\n- type: business\n  text: You may be permitted to open a Business Account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/river-financial/eligibility/river-financial-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from River Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Bitcoin Services
- Cryptocurrency
- Financial Services
- Banking
- OAuth
- Authentication
---
