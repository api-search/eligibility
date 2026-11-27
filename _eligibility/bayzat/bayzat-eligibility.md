---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Minors under the age of 18 are prohibited to register as a User of Bayzat and are not allowed to transact on Bayzat.
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
name: Bayzat
provenance_date: '2026-11-09'
provider_name: Bayzat
provider_slug: bayzat
slug: bayzat-eligibility
source_date: '2026-11-09'
source_filename: bayzat-eligibility.yml
source_heading: Eligibility
source_page: https://www.bayzat.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bayzat\naid: bayzat\nurl: https://www.bayzat.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Minors under the age of 18 are prohibited to register as a User of Bayzat and are not allowed to transact\n    on Bayzat.\n"
source_yaml_url: https://artifacts.apis.io/bayzat/eligibility/bayzat-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Bayzat's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Payroll
- Benefits
- Software-as-a-Service
- GCC
- Employee Benefits
---
