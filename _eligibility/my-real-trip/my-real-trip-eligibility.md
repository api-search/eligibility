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
  restricted_uses:
  - summary: Purchase of legally restricted goods
    text: 법령에 따라 거래가 제한되는 재화 및 용역을 구매하려는 행위
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
name: My Real Trip
provenance_date: '2026-11-10'
provider_name: My Real Trip
provider_slug: my-real-trip
slug: my-real-trip-eligibility
source_date: '2026-11-10'
source_filename: my-real-trip-eligibility.yml
source_heading: Eligibility
source_page: https://auth.myrealtrip.com/terms/policyAgreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: My Real Trip\naid: my-real-trip\nurl: https://auth.myrealtrip.com/terms/policyAgreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Purchase of legally restricted goods\n  text: 법령에 따라 거래가 제한되는 재화 및 용역을 구매하려는 행위\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/my-real-trip/eligibility/my-real-trip-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from My Real Trip's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Tourism
- Flights
- Accommodation
- Tours and Activities
- Affiliates
- MCP
- South Korea
---
