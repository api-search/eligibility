---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the full range of features in the App, you will need to create a profile. After entering your valid email address, we will send you a four-digit verification code.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Getsafe
provenance_date: '2026-11-09'
provider_name: Getsafe
provider_slug: getsafe
slug: getsafe-eligibility
source_date: '2026-11-09'
source_filename: getsafe-eligibility.yml
source_heading: Eligibility
source_page: https://www.hellogetsafe.com/en-de/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Getsafe\naid: getsafe\nurl: https://www.hellogetsafe.com/en-de/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the full range of features in the App, you will need to create a profile. After entering your valid\n    email address, we will send you a four-digit verification code.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getsafe/eligibility/getsafe-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Getsafe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Digital Insurance
- Financial Services
- Germany
- Mobile App
- Embedded Insurance
---
