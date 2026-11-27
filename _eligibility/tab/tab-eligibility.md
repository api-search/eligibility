---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are using this service as a Consumer.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent, criminal or non-Tourism uses
    text: You agree not to use the service for any fraudulent or criminal purposes, for any goods or services other than Tourism Services, or for any other purpose that we deem to be inappropriate.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We use your data in order to verify your identity and deliver the Services, as outlined in our Privacy Policy
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tab
provenance_date: '2026-11-10'
provider_name: Tab
provider_slug: tab
slug: tab-eligibility
source_date: '2026-11-10'
source_filename: tab-eligibility.yml
source_heading: Eligibility
source_page: https://book.tab.travel/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tab\naid: tab\nurl: https://book.tab.travel/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are using this service as a Consumer.\nrestricted_uses:\n- summary: Fraudulent, criminal or non-Tourism uses\n  text: You agree not to use the service for any fraudulent or criminal purposes, for any goods or services other\n    than Tourism Services, or for any other purpose that we deem to be inappropriate.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We use your data in order to verify your identity\
  \ and deliver the Services, as outlined in our Privacy Policy\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tab/eligibility/tab-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Tab's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Travel
- Tourism
- Hospitality
- Fintech
- Marketplace
- Booking
---
