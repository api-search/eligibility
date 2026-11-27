---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Troy Medicare is available to anyone who is eligible for Medicare Part A and Part B and resides in Alexander, Anson, Bladen, Buncombe, Burke, Caldwell, Catawba, Chatham, Columbus, Cumberland, Durham, Franklin, Granville, Harnett, Haywood, Henderson, Hoke, Iredell, Jackson, Lee, McDowell, Mitchell, Montgomery, Moore, Orange, Person, Polk, Richmond, Robeson, Sampson, Scotland, Swain, Transylvania, Vance, or Yancey counties in North Carolina.
  entity_types:
  - text: Troy Medicare is available to anyone who is eligible for Medicare Part A and Part B
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
name: Troy Medicare
provenance_date: '2026-11-10'
provider_name: Troy Medicare
provider_slug: troy-medicare
slug: troy-medicare-eligibility
source_date: '2026-11-10'
source_filename: troy-medicare-eligibility.yml
source_heading: Eligibility
source_page: https://troymedicare.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Troy Medicare\naid: troy-medicare\nurl: https://troymedicare.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Troy Medicare is available to anyone who is eligible for Medicare Part A and Part B and resides in Alexander,\n    Anson, Bladen, Buncombe, Burke, Caldwell, Catawba, Chatham, Columbus, Cumberland, Durham, Franklin, Granville,\n    Harnett, Haywood, Henderson, Hoke, Iredell, Jackson, Lee, McDowell, Mitchell, Montgomery, Moore, Orange, Person,\n    Polk, Richmond, Robeson, Sampson, Scotland, Swain, Transylvania, Vance, or Yancey counties in North Carolina.\n\
  entity_types:\n- type: individual\n  text: Troy Medicare is available to anyone who is eligible for Medicare Part A and Part B\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/troy-medicare/eligibility/troy-medicare-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Troy Medicare's own page on 2026-11-10.
synthetic: false
tags:
- Health Insurance
- Medicare
- Medicare Advantage
- Health Plans
- Healthcare
- Pharmacy
- Care Management
- Insurance
- Identity
---
