---
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You will not permit any User to access or use any Platform or Subscription Services in a U.S.-embargoed country or region (including Cuba, Iran, North Korea, Sudan, Syria or Crimea, or any other countries the U.S. may add to its denied-party list)
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Restricted Information without BAA
    text: (v) upload to the Services or use the Services to collect, store, or process Restricted Information unless you have entered into a Business Associate Agreement with SOCi
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SOCi
provenance_date: '2026-11-10'
provider_name: SOCi
provider_slug: soci
slug: soci-eligibility
source_date: '2026-11-10'
source_filename: soci-eligibility.yml
source_heading: Eligibility
source_page: https://www.soci.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SOCi\naid: soci\nurl: https://www.soci.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You will not permit any User to access or use any Platform or Subscription Services in a U.S.-embargoed\n    country or region (including Cuba, Iran, North Korea, Sudan, Syria or Crimea, or any other countries the U.S.\n    may add to its denied-party list)\nentity_types: []\nrestricted_uses:\n- summary: No Restricted Information without BAA\n  text: (v) upload to the Services or use the Services to collect, store, or process Restricted\
  \ Information unless\n    you have entered into a Business Associate Agreement with SOCi\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/soci/eligibility/soci-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from SOCi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Local Marketing
- Multi-Location
- Reputation Management
- Listings Management
- Social Media Management
- Reviews
- Franchise
- Local SEO
---
