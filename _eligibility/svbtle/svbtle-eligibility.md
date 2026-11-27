---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services is available only to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Services is available only to individuals who are at least 13 years old.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Svbtle
provenance_date: '2026-11-10'
provider_name: Svbtle
provider_slug: svbtle
slug: svbtle-eligibility
source_date: '2026-11-10'
source_filename: svbtle-eligibility.yml
source_heading: Eligibility
source_page: https://svbtle.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Svbtle\naid: svbtle\nurl: https://svbtle.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services is available only to individuals who are at least 13 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup process.\nminimum_age:\n  value: '13'\n  text: The Services is available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/svbtle/eligibility/svbtle-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Svbtle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blogging
- Publishing
- Content
- Writing
- Blog Platform
- Media
---
