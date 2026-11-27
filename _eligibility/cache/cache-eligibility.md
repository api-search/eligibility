---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Cache Advisors' investment advisory services are available only to residents of the United States in jurisdictions where Cache is registered.
  entity_types:
  - text: In order to become a Customer, an individual must first become a User.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Cache Securities and Cache Advisors are under no obligation to accept any individual or entity as a Customer, and may accept or reject any User in its sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cache
provenance_date: '2026-11-09'
provider_name: Cache
provider_slug: cache
slug: cache-eligibility
source_date: '2026-11-09'
source_filename: cache-eligibility.yml
source_heading: Eligibility
source_page: https://usecache.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cache\naid: cache\nurl: https://usecache.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Cache Advisors' investment advisory services are available only to residents of the United States in jurisdictions\n    where Cache is registered.\nentity_types:\n- type: individual\n  text: In order to become a Customer, an individual must first become a User.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Cache Securities and Cache Advisors are under no obligation to accept any individual or entity as a Customer,\n\
  \    and may accept or reject any User in its sole and complete discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cache/eligibility/cache-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Cache's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Investment
- Tax Optimization
- Wealth Management
- Platform
---
